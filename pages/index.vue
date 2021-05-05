<template>
  <p>
    \begin{align}
    \dot{x} &amp; = \sigma(y-x) \\
    \dot{y} &amp; = \rho x - y - xz \\
    \dot{z} &amp; = -\beta z + xy
    \end{align}
  </p>
</template>

<script>
export default {
  // 該当するページだけで読み込みたい場合
  head() {
    return {
      script: [
        {
          src: "https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"
        }
      ],
    };
  }
}
</script>
