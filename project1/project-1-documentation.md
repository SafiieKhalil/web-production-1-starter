1. Inspiration
At first, I considered creating an English language practice tool or a genre-based library, but I didn't quite know how to implement them, so I abandoned those ideas after a few attempts. I wanted to create something personal—not just a random topic, but something that resonated with my own experiences and those of the people around me, and that might potentially help others.

The design concept was inspired by Larissa Pham’s project (Poem Club), which featured a beautiful, dynamic background. I found a video of the sea and selected the fonts, buttons, and page layouts to match its blue tones. The main search term I used for inspiration was cozy lofi vibe.

2. Sketches
I didn't draw wireframes on paper or digitally. I simply had a mental image of how the pages (Home, Nature, Reading) would seamlessly connect via buttons, allowing the user to navigate easily back and forth. The visual design took shape as I actually started building the project.

3. Technical Process
I encountered a few issues while coding. The first was that the background video would freeze after playing once. After some research, I fixed this by adding the `loop` attribute to the `<video>` tag. Next, I struggled with how to make the buttons "come alive" on hover. After further research, I implemented a semi-transparent background and a glow effect:

``` CSS
.button-link:hover {
color: #ffffff; 
border-color: #ffffff; 
transform: translateY(-2px) scale(1.02);
}
```
In reality, this project took a long time; I constantly had to dig through class notes—recalling things we had covered—or search online for concepts we hadn't yet learned. I think this was my main challenge: a lack of automatic proficiency and technical knowledge.

 4. Resources
- Class notes
- https://www.youtube.com/watch?v=znqUwx0b0HI
- https://www.youtube.com/watch?v=UFVToRbniFo
- https://www.w3schools.com/html/html5_audio.asp
- https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/details
- https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/figure