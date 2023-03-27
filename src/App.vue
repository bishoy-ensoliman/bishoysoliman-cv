<template>
  <!-- Page Container -->

  <!-- Navbar -->
  <div id="navBar" class="w3-top">
    <div class="w3-bar primary-color w3-center">
      <a class="
              w3-bar-item
              w3-button
              w3-padding-large
              w3-hide-medium
              w3-hide-large
              w3-right
            " href="javascript:void(0)" @click="toggleNavShow" title="Toggle Navigation Menu"><i
          class="fa fa-bars"></i></a>
      <a href="/" class="w3-bar-item w3-button w3-padding-large">BS</a>
      <a href="mailto:contact@bishoysoliman.com" class="w3-bar-item w3-button w3-padding-large w3-hide-small"
        style="float: right;">CONTACT</a>
      <a href="/files/Bishoy_Soliman.pdf" class="w3-bar-item w3-button w3-padding-large w3-hide-small"
        style="float: right;" download>Download</a>
      <div class="w3-dropdown-hover w3-hide-small" style="float: right;">
        <button class="w3-padding-large w3-button" title="More">
          Projects <i class="fa fa-caret-down"></i>
        </button>
        <div class="w3-dropdown-content w3-bar-block w3-card-4">
          <a href="http://smartcloudsws.com" target="_blank" class="w3-bar-item w3-button">SmartCloudsws</a>
        </div>
      </div>
      <a href="#portfolio" class="w3-bar-item w3-button w3-padding-large w3-hide-small"
        style="float: right;">Portfolio</a>
    </div>
  </div>
  <div id="navDemo" class="
          w3-bar-block
          primary-color
          w3-center
          w3-hide
          w3-hide-large
          w3-hide-medium
          w3-top
        " style="margin-top: 46px">
    <a href="#portfolio" class="w3-bar-item w3-button w3-padding-large">Portfolio</a>
    <a href="mailto:contact@bishoysoliman.com" class="w3-bar-item w3-button w3-padding-large">CONTACT</a>
    <a href="/files/Bishoy_Soliman.pdf" class="w3-bar-item w3-button w3-padding-large" download>Download</a>
    <a href="http://smartcloudsws.com" target="_blank" class="w3-bar-item w3-button w3-padding-large">SmartCloudsws</a>
  </div>

  <div class="w3-content">
    <div class="w3-row-padding" style="padding-top: 50px">


      <div class="box">
        <div class="level">
          <div class="level-left">
            <div>
              <h1 class="title">
                Bishoy Soliman
              </h1>
              <p>
                <i class="fa fa-briefcase fa-fw w3-margin-right w3-large text-primary-color"></i>Computer & Systems
                Engineer
              </p>
              <p>
                <i class="fa fa-home fa-fw w3-margin-right w3-large text-primary-color"></i>Munich, Germany
              </p>
              <p>
                <i class="fa fa-envelope fa-fw w3-margin-right w3-large text-primary-color"></i><a class="link"
                  href="mailto:contact@bishoysoliman.com">contact@bishoysoliman.com</a>
              </p>
              <p>
                <i class="fa fa-linkedin fa-fw  w3-margin-right w3-large text-primary-color">
                </i>
                <a class="link" target="_blank" href="https://www.linkedin.com/in/bishoy-soliman">bishoy-soliman</a>
              </p>
              <p>
                <i class="fa fa-github fa-fw  w3-margin-right w3-large text-primary-color">
                </i>
                <a class="link" target="_blank" href="https://github.com/bishoy-ensoliman">bishoy-ensoliman</a>
              </p>
            </div>

          </div>
          <div class="level-right">
            <img src="./assets/avatar.png" alt="Avatar" />
          </div>
        </div>
      </div>



      <div class="box w3-container w3-white w3-margin-bottom">
        <h1 class="w3-text-grey w3-padding-16 title">
          <i class="
                  fa fa-suitcase fa-fw
                  w3-margin-right w3-xxlarge text-primary-color
                "></i>Work Experience
        </h1>
        <div class="w3-container">
          <h5 class="w3-opacity">
            <b>Backend Software Engineer @ Avi Medical</b>
          </h5>
          <h6 class="text-primary-color">
            <i class="fa fa-calendar fa-fw w3-margin-right"></i>Oct 2022 -
            <span class="w3-tag primary-color w3-round">Current</span>
            <span class="float-right"><i class="fa fa-map-marker fa-fw"></i>Munich, Germany</span>
          </h6>
          <ul>
            <li>
              Backend Software Engineer developing, testing, deploying software services.
            </li>
          </ul>
          <div class="technologies">
            <div class="w3-light-grey">Java</div>
            <div class="w3-light-grey">Quarkus</div>
          </div>
          <hr />
        </div>
        <div class="w3-container">
          <h5 class="w3-opacity">
            <b>Integration Manager @ Flixbus</b>
          </h5>
          <h6 class="text-primary-color">
            <i class="fa fa-calendar fa-fw w3-margin-right"></i>Jul 2021 - Sep 2022
            <span class="float-right"><i class="fa fa-map-marker fa-fw"></i>Munich, Germany</span>
          </h6>
          <ul>
            <li>
              Systems Integration Engineer Responsible for designing,
              developing and testing of business process automation and
              Systems Integration.
            </li>
          </ul>
          <div class="technologies">
            <div class="w3-light-grey">Oracle Integration Cloud</div>
            <div class="w3-light-grey">AWS</div>
            <div class="w3-light-grey">Oracle Cloud</div>
            <div class="w3-light-grey">Oracle Fusion</div>
          </div>
          <hr />
        </div>
        <div class="w3-container">
          <h5 class="w3-opacity">
            <b>Software Engineer @ EGYM GmbH</b>
          </h5>
          <h6 class="text-primary-color">
            <i class="fa fa-calendar fa-fw w3-margin-right"></i>Dec 2019 - Jun
            2021
            <span class="float-right"><i class="fa fa-map-marker fa-fw"></i>Munich, Germany</span>
          </h6>
          <ul>
            <li>Full Stack Developer and related projects DevOps.</li>
            <li>
              Systems Integration Engineer Responsible for designing,
              developing and testing of business process automation and
              Systems Integration.
            </li>
          </ul>
          <div class="technologies">
            <div class="w3-light-grey">Azure</div>
            <div class="w3-light-grey">Google cloud platform</div>
            <div class="w3-light-grey">Angular</div>
            <div class="w3-light-grey">Spring-boot</div>
            <div class="w3-light-grey">Docker</div>
            <div class="w3-light-grey">Kubernetes</div>
          </div>
          <hr />
        </div>
        <div class="w3-container">
          <h5 class="w3-opacity">
            <b>Software Engineer @ Pixelogic Media</b>
          </h5>
          <h6 class="text-primary-color">
            <i class="fa fa-calendar fa-fw w3-margin-right"></i>Jan 2019 - Nov
            2019
            <span class="float-right"><i class="fa fa-map-marker fa-fw"></i>Cairo, Egypt</span>
          </h6>
          <p>
            Full Stack Developer responsible for designing, developing and
            maintaining project modules related to the media industry:
            translation and localization and media asset management
          </p>
          <div class="technologies">
            <div class="w3-light-grey">AWS</div>
            <div class="w3-light-grey">ReactJs</div>
            <div class="w3-light-grey">Vue.js</div>
            <div class="w3-light-grey">Spring-boot</div>
            <div class="w3-light-grey">Django</div>
            <div class="w3-light-grey">Postgresql</div>
            <div class="w3-light-grey">Jenkins</div>
            <div class="w3-light-grey">Docker</div>
            <div class="w3-light-grey">Kubernetes</div>
          </div>
          <hr />
        </div>
        <div class="w3-container">
          <h5 class="w3-opacity">
            <b>Junior Software Engineer @ Bibliotheca Alexandrina</b>
          </h5>
          <h6 class="text-primary-color">
            <i class="fa fa-calendar fa-fw w3-margin-right"></i>Sep 2017 – Dec
            2018
            <span class="float-right"><i class="fa fa-map-marker fa-fw"></i>Alexandria, Egypt</span>
          </h6>
          <ul>
            <li>
              Developing, Testing, Documenting and Installing Software
              Systems.
            </li>
            <li>Developing Desktop andWeb Applications.</li>
            <li>Financial and HR processes automation.</li>
            <li>Maintaining already existing systems and support users.</li>
            <li>
              MS SQL server DB and Oracle DB development and administration.
            </li>
            <li>DB sync and systems integration.</li>
          </ul>
          <div class="technologies">
            <div class="w3-light-grey">.NET</div>
            <div class="w3-light-grey">C#</div>
            <div class="w3-light-grey">Windows server and IIS</div>
            <div class="w3-light-grey">ASP.NET</div>
            <div class="w3-light-grey">Entity Framework</div>
            <div class="w3-light-grey">MS SQL</div>
            <div class="w3-light-grey">Oracle</div>
            <div class="w3-light-grey">Sharepoint</div>
          </div>
          <hr />
        </div>
        <div class="w3-container">
          <h5 class="w3-opacity">
            <b>Teaching Assistant @ Faculty of Engineering Alexandria
              University</b>
          </h5>
          <h6 class="text-primary-color">
            <i class="fa fa-calendar fa-fw w3-margin-right"></i>Sep 2017 - Dec
            2017
            <span class="float-right"><i class="fa fa-map-marker fa-fw"></i>Alexandria, Egypt</span>
          </h6>
          <p>Tutor for Introductory Course to Computer Engineering</p>
          <br />
        </div>
      </div>

      <div class="box w3-container w3-white">
        <h1 class="w3-text-grey w3-padding-16 title">
          <i class="
                  fa fa-certificate fa-fw
                  w3-margin-right w3-xxlarge text-primary-color
                "></i>Education
        </h1>
        <div class="w3-container">
          <h5 class="w3-opacity">
            <b>Faculty of Engineering Alexandria University</b>
          </h5>
          <h6 class="text-primary-color">
            <i class="fa fa-calendar fa-fw w3-margin-right"></i>Sep 2017 - Dec
            2018
          </h6>
          <p>MSc. CourseWork Computer and Systems Engineering</p>
          <div class="technologies">
            <div class="w3-light-grey">
              Fuzzy Logic and its Engineering Applications
            </div>
            <div class="w3-light-grey">IOT</div>
            <div class="w3-light-grey">Digital Image Processing</div>
            <div class="w3-light-grey">Computer Vision</div>
            <div class="w3-light-grey">Pattern Recognition</div>
            <div class="w3-light-grey">Machine Learning</div>
            <div class="w3-light-grey">
              Machine Learning for Embedded Systems
            </div>
          </div>
          <hr />
        </div>
        <div class="w3-container">
          <h5 class="w3-opacity">
            <b>Faculty of Engineering Alexandria University</b>
          </h5>
          <h6 class="text-primary-color">
            <i class="fa fa-calendar fa-fw w3-margin-right"></i>Sep 2012 – Jun
            2017
          </h6>
          <p>BSc. Computer and Systems Engineering</p>
          <br />
        </div>
      </div>


      <div class="box">
        <h1 class="title">Skills</h1>

        <div class="tabs is-boxed">
          <ul>
            <li v-bind:class="{ 'is-active': isActive == 'programmingLanguages' }"><a
                v-on:click="isActive = 'programmingLanguages'">
                <i class="fa fa-microchip fa-fw text-primary-color"></i>Programming Languages
              </a></li>
            <li v-bind:class="{ 'is-active': isActive == 'techSkills' }"><a v-on:click="isActive = 'techSkills'">
                <i class="fa fa-gears fa-fw text-primary-color"></i>Technical Skills
              </a></li>
            <li v-bind:class="{ 'is-active': isActive == 'langs' }"><a v-on:click="isActive = 'langs'">
                <i class="fa fa-globe fa-fw w3-margin-right text-primary-color"></i>Languages
              </a></li>
          </ul>
        </div>
        <div class="tab-contents">
          <div class="content" v-bind:class="{ 'is-active': isActive == 'programmingLanguages' }">
            <div>
              <div>
                <p>JAVA</p>
                <div class="w3-light-grey w3-round-xlarge">
                  <div class="w3-round-xlarge primary-color" style="height: 24px; width: 90%"></div>
                </div>
              </div>
              <div>
                <p>PYTHON</p>
                <div class="w3-light-grey w3-round-xlarge">
                  <div class="w3-round-xlarge primary-color" style="height: 24px; width: 60%"></div>
                </div>
              </div>
              <div>
                <p>C#</p>
                <div class="w3-light-grey w3-round-xlarge">
                  <div class="w3-round-xlarge primary-color" style="height: 24px; width: 90%"></div>
                </div>
              </div>
              <div>
                <p>C</p>
                <div class="w3-light-grey w3-round-xlarge">
                  <div class="w3-round-xlarge primary-color" style="height: 24px; width: 90%"></div>
                </div>
              </div>
              <div>
                <p>C++</p>
                <div class="w3-light-grey w3-round-xlarge">
                  <div class="w3-round-xlarge primary-color" style="height: 24px; width: 60%"></div>
                </div>
              </div>
              <div>
                <p>Javascript/EcmaScript and TypeScript</p>
                <div class="w3-light-grey w3-round-xlarge">
                  <div class="w3-round-xlarge primary-color" style="height: 24px; width: 90%"></div>
                </div>
              </div>
            </div>
          </div>
          <div class="content" v-bind:class="{ 'is-active': isActive == 'techSkills' }">
            <h3 class="w3-medium subtitle">Web Technologies</h3>
            <div class="w3-text-black w3-small">
              HTML5, CSS3, JS, ES, TS, React, Vue.js, Svelte, Angular, Spring, Django,
              ASP, SharePoint, AWS, GCP, Azure, REST,WebServices, Docker, k8s,
              Jest, Enzyme, MS SQL, Oracle DB, MYSQL, Postgresql
            </div>
            <br />
            <h3 class="w3-medium subtitle">General Knowledge</h3>
            <div class="w3-text-black w3-small">
              SAP, SalesForce, Oracle Business Suite, Oracle Fusion, Oracle ERP, Big Data
              analytics, Android, QT, TensorFlow
            </div>
            <br />
            <h3 class="w3-medium subtitle">Source Control</h3>
            <div class="w3-text-black w3-small">
              github, bitbucket, gitlab, TFS
            </div>
          </div>
          <div class="content" v-bind:class="{ 'is-active': isActive == 'langs' }">
            <div class="language">
              English
              <div class="float-right">C1</div>
            </div>
            <div class="w3-light-grey w3-round-xlarge">
              <div class="w3-round-xlarge primary-color" style="height: 24px; width: 100%"></div>
            </div>
            <div class="language">
              German
              <div class="float-right">B2</div>
            </div>
            <div class="w3-light-grey w3-round-xlarge">
              <div class="w3-round-xlarge primary-color" style="height: 24px; width: 75%"></div>
            </div>
            <div class="language">
              Arabic
              <div class="float-right">Native</div>
            </div>
            <div class="w3-light-grey w3-round-xlarge">
              <div class="w3-round-xlarge primary-color" style="height: 24px; width: 100%"></div>
            </div>
            <div class="language">
              French
              <div class="float-right">A1</div>
            </div>
            <div class="w3-light-grey w3-round-xlarge">
              <div class="w3-round-xlarge primary-color" style="height: 24px; width: 25%"></div>
            </div>
          </div>
        </div>
      </div>

      <!-- End Grid -->
    </div>

    <!-- End Page Container -->
  </div>

  <footer id="footer" class="w3-container w3-center w3-margin-top primary-color">
    <p>© {{ new Date().getFullYear() }} Bishoy Soliman</p>
  </footer>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      isActive: 'programmingLanguages'
    }
  },
  methods: {
    toggleNavShow() {
      var x = document.getElementById("navDemo");
      if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
      } else {
        x.className = x.className.replace(" w3-show", "");
      }
    },
  },
};
</script>

<style>
#app {
  font-family: Roboto, sans-serif;
}

.name {
  background-color: rgba(255, 255, 255, 0.8);
  font-size: 2rem;
  border-radius: 2rem;
  padding: 0 1rem;
  margin: 0.25em;
}

.language {
  margin: 1rem 0;
}

.float-right {
  float: right;
}

.link {
  text-decoration: none;
}

.link:hover {
  text-decoration: underline;
}

.technologies {
  display: flex;
  flex-flow: row wrap;
  justify-content: flex-start;
  align-items: flex-start;
}

.technologies div {
  border-radius: 1rem;
  padding: 0 0.5rem;
  margin: 0.3rem;
}

.button {
  width: 8rem;
  height: 5rem;
  cursor: pointer;
  font-size: 2rem;
  border-radius: 1rem;
}

.primary-color,
.w3-dropdown-content,
.w3-dropdown-hover {
  color: black;
  background-color: rgba(3, 229, 97, 0.7) !important;
}

.text-primary-color {
  color: rgba(3, 229, 97, 1);
}

.w3-button:hover,
.w3-dropdown-hover:hover>.w3-button:first-child,
.w3-dropdown-click:hover>.w3-button:first-child {
  color: #000 !important;
  background-color: rgb(0, 125, 58) !important;
}

.tab-contents .content {
  display: none;
}

.tab-contents .content.is-active {
  display: block;
}
</style>