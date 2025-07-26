---
layout: publications_single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

<!-- Embedded PDF Viewer -->
<div style="
  width: 100%;
  height: 800px;
  border: 2px solid #e1e8ed;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  margin-bottom: 2em;
">
  <object data="{{ base_path }}/files/cv/cv.pdf" type="application/pdf" width="100%" height="100%">
    <!-- Fallback for browsers that don't support object tag -->
    <iframe src="{{ base_path }}/files/cv/cv.pdf" width="100%" height="100%" style="border: none;">
      <!-- Fallback if iframe also doesn't work -->
      <p style="text-align: center; padding: 2em; color: #666;">
        Your browser doesn't support PDF viewing. 
        <a href="{{ base_path }}/files/cv/cv.pdf" target="_blank" style="color: #3498db; text-decoration: none;">
          <strong>Click here to view or download the CV</strong>
        </a>
      </p>
    </iframe>
  </object>
</div>

<div style="text-align: center; margin-bottom: 2em;">
  <!-- <h2 style="margin-bottom: 1em;">Minjae Kwon - Curriculum Vitae</h2> -->
  
  <div style="margin-bottom: 2em;">
    <a href="{{ base_path }}/files/cv/cv.pdf" target="_blank" style="
      display: inline-block;
      background-color: #3498db;
      color: white;
      padding: 12px 24px;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
      margin-right: 1em;
      transition: background-color 0.3s ease;
    " onmouseover="this.style.backgroundColor='#2980b9'" onmouseout="this.style.backgroundColor='#3498db'">
      <i class="fas fa-file-pdf"></i> View Full PDF
    </a>
    
    <a href="{{ base_path }}/files/cv/cv.pdf" download="Minjae_Kwon_CV.pdf" style="
      display: inline-block;
      background-color: #27ae60;
      color: white;
      padding: 12px 24px;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
      transition: background-color 0.3s ease;
    " onmouseover="this.style.backgroundColor='#229954'" onmouseout="this.style.backgroundColor='#27ae60'">
      <i class="fas fa-download"></i> Download PDF
    </a>
  </div>
</div>


<!-- Alternative text-based links for accessibility -->
<!-- <div style="text-align: center; font-size: 0.9em; color: #666; margin-top: 1em;">
  <p>
    <strong>Having trouble viewing the PDF?</strong><br>
    <a href="{{ base_path }}/files/cv/cv.pdf" target="_blank" style="color: #3498db;">Open in new tab</a> | 
    <a href="{{ base_path }}/files/cv/cv.pdf" download="Minjae_Kwon_CV.pdf" style="color: #27ae60;">Download directly</a>
  </p>
  <p style="font-size: 0.8em; margin-top: 1em;">
    <em>Last updated: {{ "now" | date: '%B %Y' }}</em>
  </p>
</div> -->

<style>
/* Responsive design for mobile */
@media (max-width: 768px) {
  .pdf-container {
    height: 600px;
  }
  
  .pdf-buttons a {
    display: block;
    margin-bottom: 0.5em;
    margin-right: 0;
  }
}

/* Print styles */
@media print {
  .pdf-buttons,
  .fallback-links {
    display: none;
  }
}
</style>
