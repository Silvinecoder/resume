<div class="side__container">
  <div class="heading__and__socials">
    <h1><span class="flicker">C</span>ristiana <span class="fast-flicker">S</span>imoes</h1>
    <h2>Front-End Developer</h2>

    <p>
      <a class="link__container" href="mailto: creativeservicepackages@gmail.com">
        <i class="fa-solid fa-envelope fa-lg"></i>creativeservicepackages@gmail.com
      </a>
    </p> 

      <!--add full socials in the footer-->
      <p>
      <a href="https://www.linkedin.com/in/cristiana-simoes-617a56205/">
        <i class="fa-brands fa-linkedin fa-lg"></i>linkedin.com/in/cristiana-simoes-617a56205/
      </a>
    </p>
    <p>
      <a href="https://github.com/Silvinecoder">
        <i class="fa-brands fa-github-alt fa-lg"></i>github.com/Silvinecoder
      </a>
    </p>
  </div>

  <div class="education__skills__language">

    <div class="subheadings">    
      <h3>Education:</h3>
    </div>

    <div class="education">
      <h3>Certificates</h3>
      <h4>Vue JS + Google Maps API: Build Location Based Web Apps Fast By Raja Tamil</h4>
      <p><i class="fa-solid fa-calendar-days"></i>(May 2022)</p>
      <h4>The Complete Web Development Bootcamp By Dr. Angela Yu</h4>
      <p><i class="fa-solid fa-calendar-days"></i>(January 2021 - July 2021)</p>
      <h4>The complete JavaScript Course: From Zero to Hero By Johnas Schmedtmann</h4>
      <p><i class="fa-solid fa-calendar-days"></i>(April 2021 - July 2021)</p>
      <h3>University</h3>
      <h4>University Of Hertfordshire</h4>
      <p><i class="fa-solid fa-calendar-days"></i>2019-2022</p>
      <p><i class="fa-solid fa-certificate"></i>MSc Music and Sound Technology (Audio Engineering)</p>
      <h4>Anglia Ruskin University</h4>
      <p><i class="fa-solid fa-calendar-days"></i>2015-2018</p>
      <p><i class="fa-solid fa-certificate"></i>BA Hons Music Degree</p>
    </div>


    <div class="subheadings">
      <h3>Skills</h3>
    </div>

    <div class="skills">
      <h4>Front-End Skills</h4>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
      </ul>

      <h4>Libraries and Preprocessors</h4>
      <ul>
        <li>Sass/Scss</li>
        <li>Less</li>
        <li>Tailwind</li>
        <li>Bootstrap</li>
        <li>Typescript</li>
        <li>Jquery</li>
        <li>Quasar</li>
      </ul>

      <h4>FrameWorks</h4>
      <ul>
        <li>Vue.js</li>
        <li>React.js</li>
        <li>Svelte.js</li>
        <li>twig.js</li>
      </ul>

      <h4>RTE</h4>
      <ul>
        <li>Node.js</li>
      </ul>

      <h4>CMS</h4>
      <ul>
        <li>Drupal</li>
        <li>WordPress</li>
      </ul>

      <h4>Version Control</h4>
      <ul>
        <li>Git</li>
        <li>BitBucket</li>
      </ul>

      <h4>Back-End Skills</h4>
      <ul>
        <li>Python</li>
        <li>C</li>
        <li>C++</li>
        <li>MySQL</li>
      </ul>

      <h4>DevOps</h4>
      <ul>
        <li>Lando</li>
        <li>Docker</li>
      </ul>

        <h4>Designing Tools</h4>
        <p>Figma</p>
    </div>

    <div class="subheadings">
      <h3>Languages</h3>
    </div>

    <div class="languages">
      <ul>
        <li>English</li>
        <li>Portuguese</li>
      </ul>
    </div>
  </div>
</div>

<style lang="scss">
@import './scss/main.scss';
    
.side__container{
  background-color: $grey;
  padding-top: $spacer--9;

  .heading__and__socials{
    display: none;
  }

  h3{
    color: $dark-brown;
  }

  .education__skills__language{
    padding-left: $spacer--2;

    .subheadings{
      margin-top: $spacer--10;
      margin-bottom: $spacer--2;
    }
    
    ul{
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }
  }

  @media (min-width: $desktop--breakpoint) {
    padding: 0;

    .heading__and__socials{
      display: block;
    }
  }
}
</style>