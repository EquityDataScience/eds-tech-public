---
layout: default
title: System Design Diagramming
permalink: /system-design-diagramming/
---

<div class="header">
  <h1>🎨 System Design Diagramming</h1>
  <p class="subtitle">Master Excalidraw for technical interviews</p>
  <p class="time-estimate">~40 minutes to complete all exercises</p>
  <a href="https://excalidraw.com" target="_blank" rel="noopener noreferrer" class="cta-button">
    ▶ Open Excalidraw.com ↗
  </a>
</div>

<div class="info-box">
  <h3>💡 How to Use This Guide</h3>
  <ol>
    <li>Open Excalidraw.com in another browser tab</li>
    <li>Work through each exercise, practicing the skills in Excalidraw</li>
    <li>Check the box when you complete each exercise</li>
    <li>Try the timed challenges when you feel ready</li>
  </ol>
</div>

## 📖 Skill Exercises

<div class="exercise" data-id="components">
  <div class="exercise-header">
    <button type="button" class="exercise-toggle" aria-expanded="false" aria-controls="exercise-content-components">
      <div class="exercise-info">
        <div class="exercise-icon">🖥️</div>
        <div>
          <div class="exercise-title">Drawing System Components</div>
          <div class="exercise-time">⏱️ 5 min</div>
        </div>
      </div>
      <span class="chevron">▶</span>
    </button>
    <div class="checkbox-wrapper">
      <input type="checkbox" class="exercise-checkbox" aria-label="Mark as complete">
    </div>
  </div>
  <div class="exercise-content" id="exercise-content-components">
    <ol>
      <li>Press <kbd>R</kbd> for rectangles — use these for services, servers, clients, and most components</li>
      <li>Press <kbd>D</kbd> for diamonds — useful for decision points, load balancers, or routers</li>
      <li>Press <kbd>O</kbd> for ellipses — good for users, actors, or external entities</li>
      <li>Double-click any shape to add a label (e.g., "Service A", "Cache", "Database")</li>
      <li>Practice creating a mix: 2 services, 1 database, 1 cache, 1 external system</li>
    </ol>
    <div class="tip-box">
      Keep it simple — labeled rectangles work for 90% of components. Don't overthink shape choices!
    </div>
    <div class="challenge-box">
      <strong>🎯 Practice Challenge:</strong>
      <p>Draw 5 different system components with clear labels in under 2 minutes</p>
    </div>
  </div>
</div>

<div class="exercise" data-id="connections">
  <div class="exercise-header">
    <button type="button" class="exercise-toggle" aria-expanded="false" aria-controls="exercise-content-connections">
      <div class="exercise-info">
        <div class="exercise-icon">➡️</div>
        <div>
          <div class="exercise-title">Showing Data & Request Flow</div>
          <div class="exercise-time">⏱️ 5 min</div>
        </div>
      </div>
      <span class="chevron">▶</span>
    </button>
    <div class="checkbox-wrapper">
      <input type="checkbox" class="exercise-checkbox" aria-label="Mark as complete">
    </div>
  </div>
  <div class="exercise-content" id="exercise-content-connections">
    <ol>
      <li>Press <kbd>A</kbd> for arrows — these show how data or requests move between components</li>
      <li>Attach arrow endpoints to shapes (they'll snap) so they stay connected when you reorganize</li>
      <li>Use arrow direction to show request flow (who calls whom)</li>
      <li>Add small text labels near arrows to describe what's being sent</li>
      <li>Practice different arrow styles: solid for sync calls, dashed for async/events</li>
    </ol>
    <div class="tip-box">
      Clear arrows with labels tell the story of how your system works!
    </div>
    <div class="challenge-box">
      <strong>🎯 Practice Challenge:</strong>
      <p>Connect 4 components showing a request flowing through the system with labeled arrows</p>
    </div>
  </div>
</div>

<div class="exercise" data-id="boundaries">
  <div class="exercise-header">
    <button type="button" class="exercise-toggle" aria-expanded="false" aria-controls="exercise-content-boundaries">
      <div class="exercise-info">
        <div class="exercise-icon">📦</div>
        <div>
          <div class="exercise-title">System Boundaries & Grouping</div>
          <div class="exercise-time">⏱️ 5 min</div>
        </div>
      </div>
      <span class="chevron">▶</span>
    </button>
    <div class="checkbox-wrapper">
      <input type="checkbox" class="exercise-checkbox" aria-label="Mark as complete">
    </div>
  </div>
  <div class="exercise-content" id="exercise-content-boundaries">
    <ol>
      <li>Draw a large rectangle as a boundary box around related components</li>
      <li>Press <kbd>Cmd/Ctrl</kbd> + <kbd>[</kbd> to send it to the back so components stay visible</li>
      <li>Label boundaries clearly: "Internal System", "External", "Client Layer", etc.</li>
      <li>Use grouping (<kbd>Cmd/Ctrl</kbd> + <kbd>G</kbd>) to move related components together</li>
      <li>Create visual separation between what you control vs. external dependencies</li>
    </ol>
    <div class="tip-box">
      Boundaries help interviewers instantly understand your system's scope!
    </div>
    <div class="challenge-box">
      <strong>🎯 Practice Challenge:</strong>
      <p>Create a diagram with 2 distinct boundary regions containing 3 components each</p>
    </div>
  </div>
</div>

<div class="exercise" data-id="annotations">
  <div class="exercise-header">
    <button type="button" class="exercise-toggle" aria-expanded="false" aria-controls="exercise-content-annotations">
      <div class="exercise-info">
        <div class="exercise-icon">📝</div>
        <div>
          <div class="exercise-title">Technical Annotations</div>
          <div class="exercise-time">⏱️ 5 min</div>
        </div>
      </div>
      <span class="chevron">▶</span>
    </button>
    <div class="checkbox-wrapper">
      <input type="checkbox" class="exercise-checkbox" aria-label="Mark as complete">
    </div>
  </div>
  <div class="exercise-content" id="exercise-content-annotations">
    <ol>
      <li>Press <kbd>T</kbd> for text — add notes about key decisions or constraints</li>
      <li>Annotate important details: protocols, data formats, or behavior notes</li>
      <li>Create a small "notes" or "assumptions" section in a corner</li>
      <li>Use smaller font sizes for secondary information</li>
      <li>Keep annotations brief — a few words, not paragraphs</li>
    </ol>
    <div class="tip-box">
      Smart annotations show you're thinking about real-world concerns, not just drawing boxes!
    </div>
    <div class="challenge-box">
      <strong>🎯 Practice Challenge:</strong>
      <p>Add 3 meaningful technical annotations to an existing diagram</p>
    </div>
  </div>
</div>

<div class="exercise" data-id="layout">
  <div class="exercise-header">
    <button type="button" class="exercise-toggle" aria-expanded="false" aria-controls="exercise-content-layout">
      <div class="exercise-info">
        <div class="exercise-icon">🎯</div>
        <div>
          <div class="exercise-title">Professional Layout Patterns</div>
          <div class="exercise-time">⏱️ 5 min</div>
        </div>
      </div>
      <span class="chevron">▶</span>
    </button>
    <div class="checkbox-wrapper">
      <input type="checkbox" class="exercise-checkbox" aria-label="Mark as complete">
    </div>
  </div>
  <div class="exercise-content" id="exercise-content-layout">
    <ol>
      <li>Arrange components in a logical flow — typically left-to-right or top-to-bottom</li>
      <li>Put users/clients on one side, data storage on the opposite side</li>
      <li>Use consistent spacing between components (toggle grid with <kbd>Cmd/Ctrl</kbd> + <kbd>'</kbd>)</li>
      <li>Align related components horizontally or vertically</li>
      <li>Leave white space — cramped diagrams are hard to read</li>
    </ol>
    <div class="tip-box">
      A clean layout makes even complex systems look understandable!
    </div>
    <div class="challenge-box">
      <strong>🎯 Practice Challenge:</strong>
      <p>Reorganize a messy 6-component diagram into a clean, aligned layout</p>
    </div>
  </div>
</div>

<div class="exercise" data-id="visual-hierarchy">
  <div class="exercise-header">
    <button type="button" class="exercise-toggle" aria-expanded="false" aria-controls="exercise-content-visual-hierarchy">
      <div class="exercise-info">
        <div class="exercise-icon">🎨</div>
        <div>
          <div class="exercise-title">Visual Hierarchy & Emphasis</div>
          <div class="exercise-time">⏱️ 5 min</div>
        </div>
      </div>
      <span class="chevron">▶</span>
    </button>
    <div class="checkbox-wrapper">
      <input type="checkbox" class="exercise-checkbox" aria-label="Mark as complete">
    </div>
  </div>
  <div class="exercise-content" id="exercise-content-visual-hierarchy">
    <ol>
      <li>Use color sparingly to categorize or highlight (select shape → fill color)</li>
      <li>Try a simple scheme: one color for compute, another for storage, another for external</li>
      <li>Use bolder borders or fills to emphasize critical components</li>
      <li>Keep most of the diagram simple — only highlight what matters</li>
      <li>Dashed borders can indicate optional or future components</li>
    </ol>
    <div class="tip-box">
      Strategic color use guides attention — random colors create confusion!
    </div>
    <div class="challenge-box">
      <strong>🎯 Practice Challenge:</strong>
      <p>Apply a 3-color scheme to categorize components in your diagram</p>
    </div>
  </div>
</div>

<div class="exercise" data-id="multiple-flows">
  <div class="exercise-header">
    <button type="button" class="exercise-toggle" aria-expanded="false" aria-controls="exercise-content-multiple-flows">
      <div class="exercise-info">
        <div class="exercise-icon">🔀</div>
        <div>
          <div class="exercise-title">Showing Multiple Flows</div>
          <div class="exercise-time">⏱️ 5 min</div>
        </div>
      </div>
      <span class="chevron">▶</span>
    </button>
    <div class="checkbox-wrapper">
      <input type="checkbox" class="exercise-checkbox" aria-label="Mark as complete">
    </div>
  </div>
  <div class="exercise-content" id="exercise-content-multiple-flows">
    <ol>
      <li>Use different arrow styles or colors to distinguish different flows</li>
      <li>Show branching by drawing multiple arrows from one component</li>
      <li>Show merging by drawing multiple arrows into one component</li>
      <li>Consider separate "swim lanes" or regions for parallel processes</li>
      <li>Label each flow type if you have more than one</li>
    </ol>
    <div class="tip-box">
      Complex systems often have multiple paths — make each one traceable!
    </div>
    <div class="challenge-box">
      <strong>🎯 Practice Challenge:</strong>
      <p>Draw a system with 2 distinct flows (e.g., read path vs. write path) clearly differentiated</p>
    </div>
  </div>
</div>

<div class="exercise" data-id="speed">
  <div class="exercise-header">
    <button type="button" class="exercise-toggle" aria-expanded="false" aria-controls="exercise-content-speed">
      <div class="exercise-info">
        <div class="exercise-icon">⚡</div>
        <div>
          <div class="exercise-title">Speed & Efficiency</div>
          <div class="exercise-time">⏱️ 5 min</div>
        </div>
      </div>
      <span class="chevron">▶</span>
    </button>
    <div class="checkbox-wrapper">
      <input type="checkbox" class="exercise-checkbox" aria-label="Mark as complete">
    </div>
  </div>
  <div class="exercise-content" id="exercise-content-speed">
    <ol>
      <li>Use <kbd>Cmd/Ctrl</kbd> + <kbd>D</kbd> to duplicate styled components quickly</li>
      <li>Create one well-styled box, then duplicate it for consistency</li>
      <li>Learn keyboard shortcuts: <kbd>R</kbd> (rect), <kbd>A</kbd> (arrow), <kbd>T</kbd> (text), <kbd>V</kbd> (select)</li>
      <li>Use copy-paste for repeated patterns</li>
      <li>Practice: aim to draw a basic system in under 3 minutes</li>
    </ol>
    <div class="tip-box">
      In interviews, speed matters — you need to iterate and refine quickly!
    </div>
    <div class="challenge-box">
      <strong>🎯 Practice Challenge:</strong>
      <p>Time yourself: create a 5-component connected system in under 2 minutes</p>
    </div>
  </div>
</div>

<div class="challenges-section">
  <h2>⚡ Timed Challenges</h2>
  <p>Practice under time pressure — set a timer and see what you can build!</p>

  <div class="challenge">
    <h3>⏱️ 3-Minute Quick Sketch</h3>
    <p>Draw a basic system with user, service, and data store</p>
    <div class="challenge-targets">
      <div class="challenge-targets-label">Success Checklist:</div>
      <ul>
        <li>3-4 labeled components</li>
        <li>Connected with arrows</li>
        <li>Clear flow direction</li>
        <li>Readable labels</li>
      </ul>
    </div>
  </div>

  <div class="challenge">
    <h3>⏱️ 5-Minute System Overview</h3>
    <p>Create a multi-tier system with boundaries and annotations</p>
    <div class="challenge-targets">
      <div class="challenge-targets-label">Success Checklist:</div>
      <ul>
        <li>6+ components</li>
        <li>At least 2 boundary regions</li>
        <li>Labeled connections</li>
        <li>Technical annotations</li>
      </ul>
    </div>
  </div>

  <div class="challenge">
    <h3>🏆 8-Minute Complete Design</h3>
    <p>Full system diagram ready for discussion</p>
    <div class="challenge-targets">
      <div class="challenge-targets-label">Success Checklist:</div>
      <ul>
        <li>8+ components</li>
        <li>Multiple flow paths</li>
        <li>Clear visual hierarchy</li>
        <li>Assumptions noted</li>
        <li>Professional layout</li>
      </ul>
    </div>
  </div>
</div>
