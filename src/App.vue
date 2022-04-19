<template>
  <!-- Page Container -->

  <div class="w3-content w3-margin-top" style="max-width: 1400px">
    <!-- Navbar -->
    <div id="navBar" class="w3-top" style="max-width: 1400px">
      <div class="w3-bar w3-teal w3-center w3-card">
        <a
          class="
            w3-bar-item
            w3-button
            w3-padding-large
            w3-hide-medium
            w3-hide-large
            w3-right
          "
          href="javascript:void(0)"
          @click="toggleNavShow"
          title="Toggle Navigation Menu"
          ><i class="fa fa-bars"></i
        ></a>
        <a
          href="mailto:contact@bishoysoliman.com"
          class="w3-bar-item w3-button w3-padding-large w3-hide-small"
          >CONTACT</a
        >
        <a
          href="javascript:void(0)"
          @click="print"
          class="w3-bar-item w3-button w3-padding-large w3-hide-small"
          >Print</a
        >
        <div class="w3-dropdown-hover w3-hide-small">
          <button class="w3-padding-large w3-button" title="More">
            Projects <i class="fa fa-caret-down"></i>
          </button>
          <div class="w3-dropdown-content w3-bar-block w3-card-4">
            <a
              href="http://fahrschule-gruhn.de"
              target="_blank"
              class="w3-bar-item w3-button"
              >Fahrschule Gruhn</a
            >
            <a
              href="https://vodoocloud.com"
              target="_blank"
              class="w3-bar-item w3-button"
              >VodooCloud</a
            >
            <a
              href="http://smartcloudsws.com"
              target="_blank"
              class="w3-bar-item w3-button"
              >SmartCloudsws</a
            >
          </div>
        </div>
      </div>
    </div>

    <!-- Navbar on small screens (remove the onclick attribute if you want the navbar to always show on top of the content when clicking on the links) -->
    <div
      id="navDemo"
      class="
        w3-bar-block
        w3-teal
        w3-center
        w3-hide
        w3-hide-large
        w3-hide-medium
        w3-top
      "
      style="margin-top: 46px"
    >
      <a
        href="mailto:contact@bishoysoliman.com"
        class="w3-bar-item w3-button w3-padding-large"
        >CONTACT</a
      >
      <a
        href="javascript:void(0)"
        class="w3-bar-item w3-button w3-padding-large"
        @click="print"
        >Print</a
      >
      <a
        href="http://fahrschule-gruhn.de"
        target="_blank"
        class="w3-bar-item w3-button"
        >Fahrschule Gruhn</a
      >
      <a
        href="https://vodoocloud.com"
        target="_blank"
        class="w3-bar-item w3-button w3-padding-large"
        >VodooCloud</a
      >
      <a
        href="http://smartcloudsws.com"
        target="_blank"
        class="w3-bar-item w3-button w3-padding-large"
        >SmartCloudsws</a
      >
    </div>

    <!-- The Grid -->
    <div class="w3-row-padding" style="padding-top: 46px">
      <left-bar />

      <!-- Right Column -->
      <div class="w3-twothird">
        <div class="w3-container w3-card w3-white w3-margin-bottom">
          <h2 class="w3-text-grey w3-padding-16">
            <i
              class="
                fa fa-suitcase fa-fw
                w3-margin-right w3-xxlarge w3-text-teal
              "
            ></i
            >Work Experience
          </h2>
          <div class="w3-container">
            <h5 class="w3-opacity">
              <b>Integration Manager @ Flixbus</b>
            </h5>
            <h6 class="w3-text-teal">
              <i class="fa fa-calendar fa-fw w3-margin-right"></i>July 2021 -
              <span class="w3-tag w3-teal w3-round">Current</span>
              <span class="float-right"
                ><i class="fa fa-map-marker fa-fw"></i>Munich, Germany</span
              >
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
            <h6 class="w3-text-teal">
              <i class="fa fa-calendar fa-fw w3-margin-right"></i>Dec 2019 - Jun
              2021
              <span class="float-right"
                ><i class="fa fa-map-marker fa-fw"></i>Munich, Germany</span
              >
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
            <h6 class="w3-text-teal">
              <i class="fa fa-calendar fa-fw w3-margin-right"></i>Jan 2019 - Nov
              2019
              <span class="float-right"
                ><i class="fa fa-map-marker fa-fw"></i>Cairo, Egypt</span
              >
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
            <h6 class="w3-text-teal">
              <i class="fa fa-calendar fa-fw w3-margin-right"></i>Sep 2017 – Dec
              2018
              <span class="float-right"
                ><i class="fa fa-map-marker fa-fw"></i>Alexandria, Egypt</span
              >
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
              <b
                >Teaching Assistant @ Faculty of Engineering Alexandria
                University</b
              >
            </h5>
            <h6 class="w3-text-teal">
              <i class="fa fa-calendar fa-fw w3-margin-right"></i>Sep 2017 - Dec
              2017
              <span class="float-right"
                ><i class="fa fa-map-marker fa-fw"></i>Alexandria, Egypt</span
              >
            </h6>
            <p>Tutor for Introductory Course to Computer Engineering</p>
            <br />
          </div>
        </div>

        <div class="w3-container w3-card w3-white">
          <h2 class="w3-text-grey w3-padding-16">
            <i
              class="
                fa fa-certificate fa-fw
                w3-margin-right w3-xxlarge w3-text-teal
              "
            ></i
            >Education
          </h2>
          <div class="w3-container">
            <h5 class="w3-opacity">
              <b>Faculty of Engineering Alexandria University</b>
            </h5>
            <h6 class="w3-text-teal">
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
            <h6 class="w3-text-teal">
              <i class="fa fa-calendar fa-fw w3-margin-right"></i>Sep 2012 – Jun
              2017
            </h6>
            <p>BSc. Computer and Systems Engineering</p>
            <br />
          </div>
        </div>

        <!-- End Right Column -->
      </div>

      <!-- End Grid -->
    </div>

    <!-- End Page Container -->
  </div>

  <footer
    id="footer"
    class="w3-content w3-container w3-teal w3-center w3-margin-top"
    style="max-width: 1400px"
  >
    <p>© 2022 Bishoy Soliman</p>
  </footer>
</template>

<script>
import LeftBar from "./components/LeftBar.vue";

export default {
  components: { LeftBar },
  name: "App",
  methods: {
    print() {
      window.print();
    },
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
</style>