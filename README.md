# Anya Ramaswamy
### Welcome to my personal website! My name is Anya, and I am a...
1. Current high school student
2. Entrepreneur
3. Singer
4. F.R.I.E.N.D.S lover
5. Dabbler of web development!

> ```
> I'm so excited to share my journey with you all.
>       Thanks for being here!
> ```

![Alt text](https://github.com/AnyaRamaswamy/AnyaRamaswamy.github.io/blob/main/MyWebsite/images/anyamain.JPG?raw=true)

***
## Table of Contents

1. [Introduction](#introduction)
2. [Projects](#features)
3. [Essays](#contact)
4. Singing
5. Contact

## Introduction

### Education

| Year        | School                              | Learnings                                      |
|-------------|-------------------------------------|------------------------------------------------|
| K-2nd        | Julia Brown Montessori School *MD*  | Starting my first formal education experience |
| 3rd-4th      | Brooke Grove Elementary School *MD* | Transitioning from private to public school setting |
| 5th-6th      | Highcrest Middle School *IL*        | Moving from one state to another               |
| 7th-8th      | Wilmette Junior High School         | Found my love for singing and writing          |
| 9th-12th     | New Trier High School               | Dabbled in web development and starting a business |

***

### Interests

#### Favorite Book: 
Catcher in the Rye || JD Salinger
#### Favorite Movie: 
Shawshank Redemption
#### Favorite Food: 
Panang Curry from Thai Tanium Restaurant in Gaithersburg 
#### Favorite Icon: 
Tim Robbins

***

### Quotes of the Month
--
#### September Edition
--
####### Literature has always been a **huge part** of my life. To bring the novelty and fresh air some simple words can bring to humanity, I thought to share a carousel of *5 quotes* that inspired me this month. Hopefully they'll inspire you too. The writer in me sure hopes so. 

<style>
.carousel {
  position: relative;
  max-width: 600px;
  margin: auto;
  overflow: hidden;
  border: 1px solid #ddd; /* Optional border */
  border-radius: 8px; /* Optional rounded corners */
}
.carousel-content {
  display: flex;
  transition: transform 0.5s ease;
}
.carousel-slide {
  min-width: 100%;
  box-sizing: border-box;
  padding: 20px;
  text-align: center;
}
.carousel-slide blockquote {
  font-size: 1.5em;
  margin: 0;
  padding: 20px;
  border-left: 5px solid #333; /* Optional styling for the blockquote */
}
.carousel-button {
  position: absolute;
  top: 50%;
  width: auto;
  padding: 10px;
  margin-top: -22px;
  color: white;
  background-color: rgba(0,0,0,0.5);
  border: none;
  cursor: pointer;
  border-radius: 3px;
  z-index: 10;
}
.prev {
  left: 0;
}
.next {
  right: 0;
}
</style>

<div class="carousel">
  <button class="carousel-button prev" onclick="moveSlide(-1)">&#10094;</button>
  <button class="carousel-button next" onclick="moveSlide(1)">&#10095;</button>
  <div class="carousel-content">
    <div class="carousel-slide">
      <blockquote>"Some birds aren't meant to be caged." -- Steven King</blockquote>
    </div>
    <div class="carousel-slide">
      <blockquote>"The beginning is the most important part of the work." -- Plato</blockquote>
    </div>
    <div class="carousel-slide">
      <blockquote>"Doing what you love is freedom. Loving what you do is happiness." -- Lana del Ray</blockquote>
    </div>
    <div class="carousel-slide">
      <blockquote>"Life is a game that one plays according to the rules." -- JD Salinger</blockquote>
    </div>
    <div class="carousel-slide">
      <blockquote>"Challenge yourself. It's the only path that leads to growth." -- Morgan Freeman</blockquote>
    </div>
  </div>
</div>

<script>
let index = 0;
const slides = document.querySelectorAll('.carousel-slide');
const totalSlides = slides.length;

function showSlide() {
  const offset = -index * 100;
  document.querySelector('.carousel-content').style.transform = `translateX(${offset}%)`;
}

function moveSlide(step) {
  index = (index + step + totalSlides) % totalSlides;
  showSlide();
}

showSlide();
</script>


### h3
#### h4
##### h5
###### h6
## Horizontal Rules

---

**or**

***

**or**

___


## Emphasis

**This is bold text**  <!-- Bold text with double asterisks -->

__This is bold text__  <!-- Bold text with double underscores -->

*This is italic text*  <!-- Italic text with single asterisks -->

_This is italic text_  <!-- Italic text with single underscores -->

# Blockquotes

## Basic Blockquote

> This is a blockquote.

## Nested Blockquotes

> This is a blockquote.
> 
> > This is a nested blockquote.

## Blockquote with Multiple Paragraphs

> This is a blockquote with multiple paragraphs.
> 
> This is the second paragraph of the blockquote.

## Blockquote with Code

> Here is some code inside a blockquote:
> 
> ```
> function helloWorld() {
>     console.log("Hello, World!");
> }
> ```

## Blockquote with Citation

> "The only limit to our realization of tomorrow is our doubts of today."
> 
> — Franklin D. Roosevelt

## Unordered Lists

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
* Item 3

+ Item A
+ Item B
  + Subitem B.1
  + Subitem B.2

- Item X
- Item Y
  - Subitem Y.1
  - Subitem Y.2
## Mixed Lists

1. First item
   * Unordered subitem
   * Another unordered subitem
2. Second item
   1. Ordered subitem 2.1
   2. Ordered subitem 2.2
3. Third item

## Task List

- [ ] Task 1
- [x] Completed Task 2
- [ ] Task 3

## Code

Inline 'code'

Indented code

// Some comments
line 1 of code
line 2 of code
line 3 of code

Block code "fences"
...
Sample text here
...

Syntax highlighting
''' js
var foo = function(bar) {
  return bar++;
};

console.log(foo(5))

## Basic Table

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |
| Row 3 Col 1 | Row 3 Col 2 | Row 3 Col 3 |

## Aligned Table

| Left Aligned | Center Aligned | Right Aligned |
|:------------ |:--------------:| ------------:|
| Row 1 Col 1  | Row 1 Col 2    | Row 1 Col 3  |
| Row 2 Col 1  | Row 2 Col 2    | Row 2 Col 3  |
| Row 3 Col 1  | Row 3 Col 2    | Row 3 Col 3  |

[Link Text](http://url.com "Optional Title Here")


## Introduction

Welcome to the introduction section.

## Features

Here are some features.

## Contact

Contact us here.




