### Hi there 👋

<!--
**Stephane-Fidinde/Stephane-Fidinde** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<script>
function writeWord(word) {
  let i = 0;
  const interval = setInterval(function() {
    if (i >= word.length) {
      clearInterval(interval);
    } else {
      const el = document.getElementById('word');
      el.innerHTML += word[i];
      i++;
    }
  }, 200);
}

writeWord('Stephane Fidinde');
</script>
<div id="word"></div>
```
