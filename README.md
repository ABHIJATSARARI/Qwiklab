# Hi there, I'm John Doe \uD83D\uDC4B

I'm a web developer who loves to create interactive and immersive experiences.

## \uD83D\uDD25 Some of my skills

- HTML, CSS, JavaScript
- React, Vue, Angular
- Node.js, Express, MongoDB
- Three.js, WebGL, WebXR

## \uD83D\uDCF7 Check out this cool hover effect

<script src="https://unpkg.com/hover-effect"></script>
<div class="container">
  <div class="distortion" data-displacement="https://i.imgur.com/6qezCj0.jpg" data-image-1="https://i.imgur.com/5YpFtWl.jpg" data-image-2="https://i.imgur.com/3sGnEeh.jpg" data-speed-in="1.6" data-speed-out="1.6" data-easing="expo.out" data-hover="false" data-intensity="0.3" data-angle="Math.PI / 8" data-parent=".container"></div>
</div>
<script>
  new hoverEffect({
    parent: document.querySelector('.distortion'),
    intensity: document.querySelector('.distortion').getAttribute('data-intensity') || undefined,
    speedIn: document.querySelector('.distortion').getAttribute('data-speed-in') || undefined,
    speedOut: document.querySelector('.distortion').getAttribute('data-speed-out') || undefined,
    easing: document.querySelector('.distortion').getAttribute('data-easing') || undefined,
    angle: document.querySelector('.distortion').getAttribute('data-angle') || undefined,
    image1: document.querySelector('.distortion').getAttribute('data-image-1'),
    image2: document.querySelector('.distortion').getAttribute('data-image-2'),
    displacementImage: document.querySelector('.distortion').getAttribute('data-displacement')
  });
</script>
