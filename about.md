---
title: About
permalink: "/about/"
layout: page
---

<h2>Purpose</h2>
<p>We want to provide a place for students interested in technology or hoping to learn more about technology to develop and practice their skills with one another.</p>
<br>
<center><p ><strong>Board Members</strong></p></center>
<br>
<div class="manual-post">
  <div class="manual manual-title">
      <strong>Posting</strong>
  </div>
  <p>  <div class="manual-content">

      </div>
</p>
</div>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Create Pages</strong>
  </div>
<p>  <div class="manual-content">

      - Create a .md file in the root directory.<br>
      - Name the file with the desired page link name.<br>  <code>about.md</code><br><code>design.md</code><br>
      - Write the <a href="jekyll">Front Matter</a> and content in the file.
      <div class="example">
        <span class='manual'>FORMAT</span><BR>
        <pre>---
layout: page
title: String <span class="hint">Title of the webpage</span>
permalink: / String / <span class="hint">Permalink for the webpage</span>
tagline: String <span class="hint">Optional Gravity Feature : Tagline for the page</span>
---</pre>
      </div>
      <div class="example">

        <pre>---
layout: page
title:  "Science"
permalink:   /science/
tagline : "Humanity is overrated."
---</pre>
      </div>


  </div>
</p>
</div>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Create Archives/ Category Pages</strong><br>
</div><br>
<div class="archiveIntro">
  <p>
    Introducing <strong>Archive Pages</strong>.<br></p>
  <span class="archive-intro">  You can display a list of all the post corresponding to a particular category on a standalone Page using the <code>'archive'</code> layout.
</span>
</div>
<br>

<p>  <div class="manual-content">

      - Create a .md file in the root directory.<br>
      - Name the file. Preferred name will be the name of the category<br>  <code>life.md</code><br>
      - Write the <a href="jekyll">Front Matter</a> and content in the file.
      <div class="example">
        <span class='manual'>FORMAT</span><BR>
    <pre>---
layout: archive<span class="hint"> Archive Page Layout</span>
title: String <span class="hint">Title of the webpage</span>
permalink: / String / <span class="hint">Permalink for the webpage</span>
tagline: String <span class="hint"> Tagline for the page</span>
category : String <span class="hint"> Name of the category of which the page will show posts.</span>
---</pre>
      </div>
      <div class="example">

        <pre>---
layout: archive
title:  "Design"
permalink : "Design"
category: "design"
tagline: "It's all about perception."
---</pre>
    </div><br>
  </div>
</p>
</div>
