---
title: Welcome to this journey
date: 2025-08-26
---

# Welcome to this journey

_This curriculum teaches programming fundamentals that apply no matter which language you choose.
It’s designed to help you navigate the tough moments that often stop people before they even get started._

<div class="eye-container">
<a href="./01-foundations/1_intro/"><img src="resources/img/eye-img.jpeg" alt="Click to start" class="eye" id="eye" style="border-radius: 10%;"></a>
  <div class="label">Click to Start</div>
</div>

**The bad part is, most people don't realize it before it's too late. Start now and get ahead of the frustration.**

## Support

If you wanna support me, consider buying me a coffee on Ko-fi at<br /><a href="https://ko-fi.com/djblackberry64">Link to site</a><br /> or just click the button down below to get redirected:<br />
<a href="https://ko-fi.com/djblackberry64"><img src="./resources/img/Ko-Fi-new.jpg" width="400" style="border-radius: 40px"></a>

<script src='https://storage.ko-fi.com/cdn/scripts/overlay-widget.js'></script>
<script>
  kofiWidgetOverlay.draw('djblackberry64', {
    'type': 'floating-chat',
    'floating-chat.donateButton.text': 'Support me',
    'floating-chat.donateButton.background-color': '#00b9fe',
    'floating-chat.donateButton.text-color': '#fff'
  });
</script>
<script>
// Wait for the DOM to be fully loaded
document.addEventListener("DOMContentLoaded", function() {
  // Add the click event listener to the eye image
  document.getElementById('eye').addEventListener('click', function() {
    // Optional: Apply a fade-out animation for the eye container
    document.querySelector('.eye-container').style.animation = "fadeOut 0.5s forwards"; // Optional fade-out effect for eye
    // Wait for the animation to finish before redirecting
    setTimeout(function() {
      // Redirect to the curriculum page (replace 'curriculum-page' with your actual page path)
      window.location.href = "./01-foundations/1_intro/"; // Redirect to your MkDocs page (e.g., curriculum section)
    }, 500); // Delay matches the fade-out animation duration
  });
});
</script>
<style>
/* Container for the eye and label */
.eye-container {
  position: relative;
  display: inline-block;
  cursor: pointer;
  text-align: center;
}
/* Styling for the eye image */
.eye {
  width: 150px; /* Adjust based on your image */
  height: auto;
  transition: transform 0.3s ease-in-out; /* Smooth scale effect on hover */
}
/* Styling for the clickable label */
.label {
  position: absolute;
  bottom: -30px; /* Adjust this based on your image size */
  width: 100%;
  text-align: center;
  font-size: 18px;
  color: #4051b5;
  font-weight: bold;
  opacity: 0;
  transition: opacity 0.3s ease; /* Fade-in effect for the label */
}
/* Hover effects for the eye (slightly zoom-in) */
.eye-container:hover .eye {
  transform: scale(1.1); /* Eye grows slightly */
}
/* Fade-in effect for the label when hovering */
.eye-container:hover .label {
  opacity: 1; /* Fade in the label */
}
/* Optional: Pulsing animation for eye */
@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}
.eye-container {
  animation: pulse 1.5s infinite; /* Gentle pulsing effect */
}
</style>
