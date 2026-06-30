# Project 2
1. Inspiration
To be honest, I didn't have anything specific in mind. I usually create posters in Figma or Photoshop and enjoy working with lots of images, but replicating that style in HTML turned out to be very difficult. Initially, I started designing the poster as if I were working in Figma, but it ended up looking more like a website—a point my partner raised during our group session. So, I decided to try something new; after seeing Swiss-style posters in the inspiration links, I attempted to create a design in that style.

After looking at posters in this style, I noticed a strong emphasis on words and geometric shapes. I began experimenting with the word "Crimea" (my home region) and circles. I chose circles because, in my view, shapes with angles can feel "sharp" or off-putting; since "home" represents something familiar and comforting, I wanted to convey that feeling through the shape itself.

2. Sketches and ideas
I never make rough sketches; that approach simply doesn't work for me. I can't come up with anything worthwhile until I actually sit down and start working. Everything I created emerged gradually during the actual design process.

3. Technical process and experiments

Since I didn't have a clear mental image from the start, my workflow mostly consisted of a cycle of creating and deleting elements. This sometimes led to issues—for instance, failing to delete a snippet of old code, which caused the new code to malfunction.

I also ran into a problem where the circles were overlapping the text after I placed it. I had to experiment with the `z-index` property. I set the circles to `z-index: 1` and the text and gallery elements to `z-index: 2` so that the text would sit neatly on top of the circles.

 Once most of the visual design and CSS were in place, I began adapting the poster for different sizes. Initially, I had set the poster to occupy about 30% of the screen width, but when I expanded it to fill the layout, it stretched across almost the entire horizontal span of the screen.

After reviewing the code in the inspector, I realized that `width: 100%` was working correctly, but the upper limit (`max-width: 1100px`) was too high. I manually tested different values ​​using the inspector and ultimately reduced the `max-width` to 850px. This made the poster look more proportional.
![Error1](/Users/safiiekhalilaieva/Desktop/web-production-1-starter/project2/images/Error1.png)
![Solution1](/Users/safiiekhalilaieva/Desktop/web-production-1-starter/project2/images/Solution1.png)

Additionally, when resizing the browser window, half of the poster would literally disappear or get cut off at the top. I changed the `align-items` property from `center` to `flex-start` for the `body` element, which fixed the issue and made everything work as intended.
![Error2](/Users/safiiekhalilaieva/Desktop/web-production-1-starter/project2/images/Error2.png)
![Solution2](/Users/safiiekhalilaieva/Desktop/web-production-1-starter/project2/images/Solution2.png)

4. Resources used

https://www.w3schools.com/cssref/css3_pr_align-items.php-    align-items:flex-start;
https://www.w3schools.com/cssref/css3_pr_border-radius.php-    border-radius:50%; 
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/letter-spacing-    letter-spacing:10px;
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/justify-content-    justify-content:space-between;


