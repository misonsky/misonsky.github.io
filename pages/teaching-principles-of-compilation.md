---
layout: news
title: Principles of Compilation
keywords: Yongkang Liu, teaching, compilation
description: Course page for Principles of Compilation
permalink: /teaching/principles-of-compilation/
css:
  - pages/teaching.css
---

<div class="course-hero">
  <p class="teaching-eyebrow">Course Detail</p>
  <h2>Principles of Compilation</h2>
  <p class="teaching-intro">
    This course introduces the complete workflow of a compiler, from source language analysis to optimized target code generation.
    It combines formal concepts with implementation practice so that students can understand both the theory and the engineering pipeline.
  </p>
  <div class="course-actions">
    <a class="course-backlink" href="{{ '/teaching/' | relative_url }}">Back to Teaching</a>
  </div>
</div>

<div class="course-meta">
  <div class="course-meta__item">
    <span class="course-meta__label">Audience</span>
    <span class="course-meta__value">Undergraduate students in computer science</span>
  </div>
  <div class="course-meta__item">
    <span class="course-meta__label">Format</span>
    <span class="course-meta__value">Lecture + programming exercises</span>
  </div>
  <div class="course-meta__item">
    <span class="course-meta__label">Goal</span>
    <span class="course-meta__value">Build a systematic understanding of compiler construction</span>
  </div>
</div>

<div class="course-outline">
  <h3>Lecture Schedule</h3>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 1</div>
    <h4>Introduction to Compilers and Language Translation</h4>
    <p>What compilers do, the phases of compilation, interpreters vs. compilers, and representative programming languages.</p>
    <p><strong>References:</strong> Aho et al., Ch. 1; Appel, Ch. 1.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 2</div>
    <h4>Formal Languages and Lexical Analysis</h4>
    <p>Regular expressions, finite automata, tokenization, and how lexical analyzers are designed and implemented.</p>
    <p><strong>References:</strong> Aho et al., Ch. 2-3; flex documentation.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 3</div>
    <h4>Context-Free Grammars and Parsing Basics</h4>
    <p>BNF, derivation, parse trees, ambiguity, and the relationship between syntax design and parsing complexity.</p>
    <p><strong>References:</strong> Aho et al., Ch. 4; Grune and Jacobs, selected sections.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 4</div>
    <h4>Top-Down Parsing</h4>
    <p>Recursive descent, FIRST/FOLLOW sets, LL(1) parsing, and grammar transformation techniques.</p>
    <p><strong>References:</strong> Aho et al., Ch. 4; lecture notes on LL parsing.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 5</div>
    <h4>Bottom-Up Parsing</h4>
    <p>Shift-reduce parsing, LR ideas, SLR/LALR concepts, and practical parser generators.</p>
    <p><strong>References:</strong> Aho et al., Ch. 4; yacc/bison tutorials.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 6</div>
    <h4>Syntax-Directed Translation</h4>
    <p>Syntax-directed definitions, attributed grammars, semantic actions, and constructing syntax trees.</p>
    <p><strong>References:</strong> Aho et al., Ch. 5.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 7</div>
    <h4>Semantic Analysis and Symbol Tables</h4>
    <p>Scope, type checking, symbol management, declaration-use chains, and semantic constraints in programming languages.</p>
    <p><strong>References:</strong> Aho et al., Ch. 6; Appel, semantic analysis chapters.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 8</div>
    <h4>Intermediate Representations</h4>
    <p>Abstract syntax trees, three-address code, control-flow graphs, and the role of IR in optimization.</p>
    <p><strong>References:</strong> Aho et al., Ch. 6-8; Cooper and Torczon, IR chapters.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 9</div>
    <h4>Run-Time Environments</h4>
    <p>Activation records, procedure calls, parameter passing, stack management, and memory layout.</p>
    <p><strong>References:</strong> Aho et al., Ch. 7; Appel, run-time environment chapters.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 10</div>
    <h4>Code Generation Fundamentals</h4>
    <p>Instruction selection, addressing modes, evaluation order, and target-machine considerations.</p>
    <p><strong>References:</strong> Aho et al., Ch. 8; Muchnick, code generation overview.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 11</div>
    <h4>Local Optimization</h4>
    <p>Constant folding, common subexpression elimination, dead code elimination, and peephole optimization.</p>
    <p><strong>References:</strong> Aho et al., Ch. 8-9; Muchnick, optimization basics.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 12</div>
    <h4>Data-Flow Analysis</h4>
    <p>Reaching definitions, liveness, available expressions, and iterative data-flow frameworks.</p>
    <p><strong>References:</strong> Aho et al., Ch. 9; Cooper and Torczon, data-flow analysis chapters.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 13</div>
    <h4>Register Allocation</h4>
    <p>Interference graphs, graph coloring, spilling, and trade-offs in resource-constrained code generation.</p>
    <p><strong>References:</strong> Appel and George, register allocation; Muchnick, relevant chapter.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 14</div>
    <h4>Optimization for Modern Architectures</h4>
    <p>Instruction scheduling, machine dependence, and practical issues when targeting realistic hardware.</p>
    <p><strong>References:</strong> Muchnick, advanced optimization sections.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 15</div>
    <h4>Mini Compiler Project Workshop</h4>
    <p>Integrating lexer, parser, semantic analyzer, and code generator into a small end-to-end compiler.</p>
    <p><strong>References:</strong> Project handout; flex/bison examples; LLVM Kaleidoscope tutorial.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 16</div>
    <h4>Course Review and Frontiers</h4>
    <p>Compiler infrastructure, domain-specific languages, JIT compilation, and connections to modern AI systems.</p>
    <p><strong>References:</strong> LLVM documentation; selected survey readings.</p>
  </div>
</div>

<div class="teaching-section">
  <h3>Core References</h3>
  <ul class="teaching-list">
    <li>Alfred V. Aho, Monica S. Lam, Ravi Sethi, Jeffrey D. Ullman. <em>Compilers: Principles, Techniques, and Tools</em>.</li>
    <li>Andrew W. Appel. <em>Modern Compiler Implementation</em>.</li>
    <li>Keith D. Cooper, Linda Torczon. <em>Engineering a Compiler</em>.</li>
    <li>Steven S. Muchnick. <em>Advanced Compiler Design and Implementation</em>.</li>
  </ul>
</div>

<div class="teaching-section">
  <h3>Assignments and Assessment</h3>
  <ul class="teaching-list">
    <li><strong>Homework:</strong> Regular exercises on automata, grammars, parsing, semantic analysis, and optimization.</li>
    <li><strong>Programming Project:</strong> Build a mini compiler or implement key modules such as a lexer, parser, or intermediate-code generator.</li>
    <li><strong>Class Participation:</strong> In-class discussion on design trade-offs in compiler construction.</li>
    <li><strong>Final Assessment:</strong> Written exam or project presentation, depending on course arrangement.</li>
  </ul>
</div>

<div class="teaching-section">
  <h3>Lecture Slides and Course Materials</h3>
  <ul class="teaching-list">
    <li>Lecture 1-4 slides: <em>to be uploaded</em></li>
    <li>Lecture 5-8 slides: <em>to be uploaded</em></li>
    <li>Lecture 9-12 slides: <em>to be uploaded</em></li>
    <li>Lecture 13-16 slides: <em>to be uploaded</em></li>
    <li>Programming assignment handouts: <em>to be uploaded</em></li>
  </ul>
  <p>You can later replace these placeholders with direct PDF, PPT, or ZIP download links.</p>
</div>
