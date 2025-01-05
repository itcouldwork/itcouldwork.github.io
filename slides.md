---
author: Spiced Academy
title: True Rosemary
subtitle: Final Project
date: 06.01.2025 - 03.02.2025
theme: moon # https://revealjs.com/themes/
transition: concave # https://revealjs.com/transitions/
# see all the options here: https://revealjs.com/config/
highlight-style: breezeDark
progress: true
slideNumber: true
hash: true
navigationMode: linear
autoPlayMedia: true

---

# What is the Final Project? 


### 🏁

::: incremental
- It is a SHOWCASE of what you have learned
- No need for ground-breaking discoveries or inventions. 
- Only if you want to...
- There will be no grades...
  but certain expectations:
- follow the [data analytics workflow](http://spiced-12-weeks-da.s3-website.eu-central-1.amazonaws.com/images/da_workflow.png) or come up with you own data analytics related approach
:::

# Timeframe 

### 📆

::: incremental
- Graduation: Monday  <font class="highlight">03.02.2025</font> at <font class="highlight">15:00 PM</font>
- Total time: 19 days + graduation day
- Stand-Up Meetings on Campus 
    - Fri <font class="highlight">10.01.</font> at <font class="highlight">10:00</font>
    - Thu <font class="highlight">16.01</font> at <font class="highlight">10:00</font>
    - Thu <font class="highlight">23.01</font> at <font class="highlight">10:00</font>
    - Fri <font class="highlight">31.01</font> at <font class="highlight">10:00</font>
- besides you can decide working on-site or off-site
:::

# Guidelines / Tips for Final Project Presentations

### ⏱


- **7-8** minutes followed by Q&A (10 min MAX)
- and it always gets a bit longer...


### 😀

- you can start by saying your name, 
 the name of your project 
 and a very brief description of what your project is about
- talk loud
- be confident and proud of what you have achieved


### 🖼

- ~one slide/min.
- one image, four points max. per slide.


### 💼 

::: incremental 
- Start with **why**, a problem, questions...
- Writing down a central statement in one short sentence would help to keep focus on your goals
- For the presentation structure – 3-4 main points are sufficient
- You don't need to talk about everything you did... pick the best parts! 
:::

### 🚫

 - **no** raw code / Jupyter Notebook
 - if nescessary, show max <= 10 lines of code at a time

### 📖 

- show some raw numbers/ descriptive statistics
- tell stories, mishaps, basics, funny details

### ⚙️

- say something about your **TECH STACK**

### 🗣

- in case you do a live demo...
- demo working software only
- make sure that your code is tested 
- does it work offline?
- have a Backup (PDF, video, screenshots etc)

### 🔌

- do a **TECH CHECK**!! (e.g. HDMI cable, adaptors, readablity, resolution etc.)

### 🙊

::: incremental 
- mistakes are not a problem
- just keep going
- **DO NOT apologize**
:::

###  🤖

::: incremental 
- focus on results
- focus on showing off the features that work
- don't talk about things you weren't able to finish
- **DO NOT apologize**
- ...it is completely fine to mention it as features  you'd like to add in the future.
:::

### ⁉️

- expect questions from the audience
- if you are not sure of the answer, say that you don't know and that's about it

### 🛑

- stop working on your project **early enough**
- you will ALWAYS feel like you can do more

### 👏

 - you have worked hard for this
 - be proud of your work


# reveal.js


### What can you do with `reveal.js` 

- `.html` presentations can be viewed in any webbrowser
- write your slides in markdown
- include interactive figures, videos, code, math, ...
- fine tune the presentation via `.css`

### Requirements

- `pandoc` to transform markdown into html
- get it from [here](https://pandoc.org/)


### Usage

OS
```shell
pandoc -t revealjs slides.md -o slides.html  \
	--mathjax \
	--standalone \
	--css=styles.css \
	--css=https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css
```
WINDOWS
```shell
pandoc -t revealjs slides.md -o slides.html  ^
	--mathjax ^
	--standalone ^
	--css=styles.css ^
	--css=https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css
```


### Tables

#### Test the new headline


| | A | B |
| :---| :---: | :---: |
| <i class="fas fa-clock"></i> | 100 | 400 |
| <i class="fas fa-plus"></i> | 200 | 300n |


### Videos


<iframe data-autoplay width="100%" height="400px" src="https://www.youtube.com/embed/Wfoy_OvNDvw"></iframe>



### Fragments

::: incremental

- Eat spaghetti
- Drink wine
- Do something else

:::


### Plots

<iframe scrolling="no" style="border:none;" seamless="seamless" data-src="assets/plotly_example.html" height="450" width="100%"></iframe>


### Plot2

**hello**

<iframe scrolling="no" style="border:none;" seamless="seamless" data-src="assets/plotly_example.html" height="450" width="100%"></iframe>


### Math

$$
f(x, y) = \frac{\sqrt{x^2+y^2}}{x+y}
$$

### Code

```python
def fun(a, b):
    print('add numbers')
    return a+b
fun(2, 2)
```

### DataFrame converted to markdown

```python
print(df.to_markdown())   
```

|    | animal_1   | animal_2   |
|---:|:-----------|:-----------|
|  0 | elk        | dog        |
|  1 | pig        | quetzal    |


### Images

![](assets/coding.jpg){ width=40% }

<span class="smallfont">Photo by <a href="https://unsplash.com/@arifriyanto?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Arif Riyanto</a> on <a href="https://unsplash.com/s/photos/coding?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>


### CSS Styling

You can

<p class="smallfont"> change the fontsize </p>

<p class="highlight"> or the color </p>

with a separate stylesheet (`styles.css`)! 



### Links

- [Awesome projects](https://github.com/NirantK/awesome-project-ideas)
- [Awesome datasets](https://github.com/awesomedata/awesome-public-datasets)
- [DrivenData Competitions](https://www.drivendata.org/)
- [Kaggle Competitions](https://www.kaggle.com/competitions)
- [Spiced Project Ideas](https://spiced.space/data-basils/da-course/09-final-project/project-ideas.html)

### Fontawesome icons

<i class="fas fa-file-code"></i>
<i class="fab fa-github-square"></i>
<i class="fab fa-codepen"></i>
<i class="fab fa-snapchat-ghost"></i>

[Fontawesome Website](https://fontawesome.com/icons/)