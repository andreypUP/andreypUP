<h2 align="center">
  <span class="neon" id="neon-name"></span>
</h2>
<p align="center">
  Computer Engineering | MSU-IIT<br>
  Algorithms & Competitive Coding<br>
  Software Engineer
</p>

<style>
  .neon {
    color: #fff;
    text-shadow: 0 0 5px #0ff, 0 0 10px #0ff;
    animation: flicker 3s infinite alternate;
  }
  @keyframes flicker {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.7; }
  }
</style>

<script>
  const name = "Hi there! I'm Mark Andrey";
  let i = 0;
  
  function typeWriter() {
    if (i < name.length) {
      document.getElementById("neon-name").innerHTML += name.charAt(i);
      i++;
      setTimeout(typeWriter, 120); // Chill pace
    }
  }
  
  window.onload = typeWriter;
</script>
