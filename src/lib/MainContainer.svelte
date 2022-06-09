<div class="main__container">
    <div class="heading__and__socials">
      <h1><span class="flicker">C</span>ristiana <span class="fast-flicker">S</span>imoes</h1>
      <h2>Front-End Developer</h2>
  
      <p>
        <a class="link__container" href="mailto: creativeservicepackages@gmail.com">
          <i class="fa-solid fa-envelope fa-lg"></i> creativeservicepackages@gmail.com
        </a>
      </p> 
  
        <!--add full socials in the footer-->
        <p>
        <a href="https://www.linkedin.com/in/cristiana-simoes-617a56205/">
          <i class="fa-brands fa-linkedin fa-lg"></i> linkedin.com/in/cristiana-simoes-617a56205/
        </a>
      </p>
      <p>
        <a href="https://github.com/Silvinecoder">
          <i class="fa-brands fa-github-alt fa-lg"></i> github.com/Silvinecoder
        </a>
      </p>
    </div>
    <div class="career__and__work__container">
      <div class="career__container">
        <h2>Career Objective</h2>
        <p>Front-end developer with over one year of experience in responsive website design and a firm believer in the mobile-first approach. After successfully building WordPress and Drupal websites, I am eager to continue my Career, expanding my framework skills. </p>
      </div>
      <div class="work__container">
        <h2>Work Experience</h2>
        <a href="https://www.versantus.co.uk/"><h3>Versantus</h3></a> 
        <h4>Front-End Developer</h4>
        <div class="work-place">
          <p><i class="fa-solid fa-calendar-days"></i> August 2021 - current</p>
          <p><i class="fa-solid fa-location-dot"></i> Frieze Farmhouse, Oxford</p>
        </div>
        <ul>
          <li>Maintained and developed commercial websites using WordPress and Drupal CMS, Twig, SCSS, Bootstrap, and Jquery.</li>
          <li>Used Drupal Mosaic WebKit to develop Oxford University websites, including the 
            <a href="https://www.spi.ox.ac.uk/">Department of Social Policy and Intervention</a></li>
          <li>Contributed to a React Native app project by developing features and fixes for the app. </li>
          <li>Worked in an agile environment with weekly stand-ups, sharing knowledge with teammates and working closely with the project manager to ensure that every product met the versatile, modern, and performant requirements.</li>
          <li>Followed best practices and guidelines, including being a part of developing a Drupal starter Kit for future development practices.</li>
          <li>Debug technical issues for Customer service, including style, configuration, security updates and deployment.</li>
        </ul>
      </div>
      <div class="project__container">
        <h2>Projects</h2>
        <a href="https://www.versantus.co.uk/"><h3>TaxiToursFernandes</h3></a> <!--Change the href-->
        <h4>Full-Stack Developer</h4>
        <ul>
          <li>Built a full-stack Uber influenced web app for a taxi company.</li>
          <li>The app is built with Vue.js using Quasar to deploy it on the Web as a SPA, PWA, and SSR to a Mobile App in a single-code base.</li>
          <li>It uses GoogleMaps Api and typescript to allow users to select their destinations and store their data on Google FireBase. The app also has a GPS for users to track the vehicle's movement.</li>
        </ul>
      </div>
      <div class="pdf__container">
        <h4><a href="/assets/CristianaSimoesResume.pdf" download>CristianaSimoesResume.pdf</a></h4>
      </div>
    </div>
  </div>

<style lang="scss">
@import './scss/main.scss';

.main__container{

    .career__and__work__container{
        margin: $spacer--10 0 $spacer--13 $spacer--2;
        grid-area: 2;

        a{
            animation: glow 3s ease-in-out infinite alternate;
            @include glow-animation;
        }

        .career__container, .work__container, .project__container{
          margin-bottom: $spacer--12;
        }

        .work__container{

            h3{
                margin-bottom: 0;
            }

            .work-place{
                display: grid;
                grid-template-columns: 1fr 1fr;
            }
        }

        .work__container, .project__container{
            ul{
                list-style-type: circle;
                margin-left: $spacer--4;
            }
        }

        .pdf__container{
              text-align: center;
        }
    }

    @media (min-width: $desktop--breakpoint){

        .heading__and__socials{
            display: none;
        }

        .career__and__work__container{
            grid-area: inherit;
            margin-bottom: 0;
        }
    }
}
  </style>