<template>
  <div class="container grid animation-fade">
    <p style="visibility: hidden"></p>
    <footer>
      <ul>
        <li>
          <a href="https://github.com/seyidayo">Github</a>
        </li>
        <li>
          <a
            href="https://docs.google.com/document/d/14aiG74XhxphzfW3ytktAowyGHGGeg4iQRl0V34OjfWA/edit?usp=sharing"
          >Resume</a>
        </li>
        <li>
          <a href="https://codepen.io/seyidayo/">CodePen</a>
        </li>
        <li>
          <a href="https://www.linkedin.com/in/faithidowu/">LinkedIn</a>
        </li>
        <li>
          <a href="https://twitter.com/faithidowu_">Twitter</a>
        </li>
      </ul>
      <p style="margin-top: 60px">
        <b>
          Faith Idowu - Frontend Engineer - copyright &copy;
          {{ new Date().getFullYear() }}
        </b>
      </p>
    </footer>
  </div>
</template>
<style lang="scss" scoped>
p {
  margin: var(--max-padding) 0;
  text-align: left;
}

footer {
  font-size: 1.2rem;
  ul {
    display: grid;
    gap: 30px;
    grid-template-columns: repeat(2, 1fr);
  }
  @media (min-width: 1024px) {
    text-align: center;
    ul {
      grid-template-columns: repeat(5, 1fr);
    }
  }

  li {
    list-style-type: none;
    text-align: left;
    margin: 0;
  }
  padding-block-start: 4rem;
}
</style>
