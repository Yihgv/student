---
layout: blogs 
title: Blogs
search_exclude: true
permalink: /blogs/
---

## Open Kasm2 system
- Go to https://kasm.opencodingsociety.com

- Use your github account to sign in 



## First time set-up
- Double click the blank place to open a terminal
- Type in and run line by line the code below

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">mkdir </span>opencs
<span class="nb">cd </span>opencs
git clone https://github.com/Open-Coding-Society/student.git
<span class="nb">cd </span>student/
./scripts/activate.sh <span class="c">
# prompts for Yihgv and r13302223015@qq.com </span>
./scripts/venv.sh
code <span class="nb">.</span>
</code></pre></div></div>



## Open VS code 
</p>

<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">cd </span>opencs/student
<span class="nb">source </span>venv/bin/activate <span class="c"># activate Python virtual environment</span>
code <span class="nb">.</span>
</code></pre></div></div>

  - Start a session to work in VSCode
  - You can work in it your student folder now
