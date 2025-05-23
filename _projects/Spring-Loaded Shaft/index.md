---
layout: post
title: Spring-Loaded Cutting Head
description:  To reduce wear and manual adjustment in the pelletizer cutting process, I redesigned the existing cutting head with a spring-loaded mechanism. This ensures constant blade pressure against the breaker head, improving blade lifespan and reducing downtime.
skills: 
  - SolidWorks
  - Mechanical Design
  - DFM/DFA
  - Prototyping
  - Problem Solving

main-image: /project2.jpg
---

---
# Header 1 
Used for the title (already generated automatically at the top)

## Background & Objective
The original pelletizer blades wore quickly and required frequent manual adjustment to maintain blade-to-breaker head contact. The goal was to automate this adjustment and increase blade longevity. A worn-out pelletizer head is shown in Figure 1.

*insert image*

## Design and Prototyping Process
I began by disassembling the original cutting head from the pelletizer machine to fully understand its form and function. After carefully measuring all critical dimensions, I created a 3D model in SolidWorks. From there, I modified the design to incorporate a spring-loaded mechanism that would apply constant pressure to keep the blades flush against the breaker head.

Several design iterations were explored to ensure proper material compatibility, spring force optimization, and ease of assembly. Once finalized, the modified cutting head was fabricated and assembled as a prototype for testing. THe Solidworks drawings and prototype is shown in Figure 2 and Figure 3, respectively.

*insert drawings*

*insert prototype*

## Outcomes & Impact 
- Improved quality and consistency of plastic pellets
- Reduced pelletizer machine downtime by 30%
- Increased blade lifespan

### Header 3 
Use this to have subsection if needed


## Embedding images 
### External images
{% include image-gallery.html images="https://live.staticflickr.com/65535/52821641477_d397e56bc4_k.jpg, https://live.staticflickr.com/65535/52822650673_f074b20d90_k.jpg" height="400"%}
<span style="font-size: 10px">"Starship Test Flight Mission" from https://www.flickr.com/photos/spacex/52821641477/</span>  
You can put in multiple entries. All images will be at a fixed height in the same row. With smaller window, they will switch to columns.  

### Embeed images
{% include image-gallery.html images="project2.jpg" height="400" %} 
place the images in project folder/images then update the file path.   


## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. <br>
*Example* : https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="MhVw-MHGv4s" autoplay= "false"%}
{% include youtube-video.html id="XGC31lmdS6s" autoplay = "true" %}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 pixels x 315 pixels.  

The width of the video below. Regardless of initial width, all the videos is responsive and will fit within the smaller screen.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "900px" %}  

<br>

## Adding a hozontal line
---

## Starting a new line
leave two spaces "  " at the end or enter <br>

## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header


