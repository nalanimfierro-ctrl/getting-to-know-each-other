# getting-to-know-each-other
## Credits: 
Nalani Fierro
Getting-to-Know-Each-Other
credit chatgpt
credit W3schools
credit W3C validator

I asked chatgpt "How do I add my email as a HTML link in my code for a website about myself
Chat gpt came back with "To add your email as a clickable HTML link on your website (so users can click it and open their email client), use the mailto: link format in an <a> (anchor) tag." and the example "<a href="mailto:yourname@example.com">yourname@example.com</a>" which I did use in my code.
I also asked Chatgpt "how to add an outside link for a website to my code," to which chatgpt replied "To add a link to an external website in your HTML code, use the <a> tag with the href attribute," and gave the example "<a href="https://www.example.com">Visit Example</a>" that I used in my code.
I asked chaptgpt how to integrate a spotify song and it gave me <!-- Spotify embed for a specific track -->
    <iframe id="spotifyPlayer"
        src="https://open.spotify.com/embed/track/6VNXmo59yDYgcwLS17UNAW?utm_source=generator"
        width="1000"
        height="152" 
        allowfullscreen="" 
        allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
        loading="lazy">
    </iframe>
    which I implemented and spliced into my code. I later added the additional question of integrating script to make it so I could rotate songs which I implmented into my code as well.
    I also asked to show me how to create a slideshow effect with my photos to which I used  <img id="slideshow" src="me-800-by-800.jpg" alt="" width="300">

  <script>
    const images = [
      'me-800-by-800.jpg',
      'me2-test-800.jpg',
      'group-800-by-800.jpg',
      'dogs1-800-by-800.jpg',
      'dogs2-800.jpg',
      'dogs3-800.jpg'
    ];
    let currentIndex = 0;
    const imgElement = document.getElementById('slideshow');
    setInterval(() => {
      currentIndex = (currentIndex + 1) % images.length; // loop back to start
      imgElement.src = images[currentIndex];
    }, 3000); // change image every 10 seconds
  </script>
  this code to create. I did change some things but the general layout of the code is the same.

credit W3schools
I found in W3schools website how to add an unordered list and an ordered list, and how to add and center an image. I also found how to do all the sytle code in the W3schools website.

Credit W3C validator for validating my code