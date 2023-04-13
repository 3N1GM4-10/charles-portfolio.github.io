<template>
  <div class="max-w-7xl m-center pt-20 pb-20">
    <div
      class="about-me text-center mt-10 md:mt-32"
      data-aos="fade-up"
      data-aos-delay="100"
      data-aos-duration="800"
    >
      <h2 class="text-5xl dark:text-white">About Me</h2>
      <span class="f-gray text-sm dark:text-white">Personal</span>
    </div>
    <div
      class="details flex mt-20 md:flex-col-reverse lg:flex-row flex-col-reverse"
    >
      <div
        class="image lg:w-3/6 mt-12 lg:m-auto"
        data-aos="fade-right"
        data-aos-delay="500"
        data-aos-duration="500"
      >
        <img
          class="w-11/12 rounded-md drop-shadow-lg m-auto lg:m-0"
          src="https://kinsta.com/wp-content/uploads/2021/11/front-end-developer-1200x675.png"
          alt=""
        />
      </div>
      <div
        class="information lg:w-3/6 flex flex-col"
        data-aos="fade-right"
        data-aos-delay="1200"
        data-aos-duration="500"
      >
        <div
          class="cover-letter f-gray text-lg pb-7 dark:text-white text-center lg:text-left md:justify-center lg:justify-start"
        >
        Hello, and thank you for visiting my portfolio! I am a recent graduate of a kodeGo Full Stack Web development bootcamp, where I gained hands-on experience in building web applications and honed my skills in HTML, CSS, and JavaScript.

        I am excited to apply my skills to real-world projects and collaborate with other professionals in the industry. During my bootcamp, I worked on several group projects that required me to communicate effectively with my team members and problem-solve in a fast-paced environment.

        </div>
        <div
          class="summary-experience flex text-center justify-center lg:justify-start"
        >
          <!-- <div class="years-exp mr-5 w-2/12">
            <h2 class="text-3xl f-dark-blue font-extrabold dark:text-blue-500">
              04+
            </h2>
            <span class="text-sm f-gray dark:text-white"
              >Years of Experience</span
            >
          </div> -->
          <!-- <div class="projects mr-5 w-2/12">
            <h2 class="text-3xl f-dark-blue font-extrabold dark:text-blue-500">
              10+
            </h2>
            <span class="text-sm f-gray dark:text-white"
              >Completed projects</span
            >
          </div> -->
          <!-- <div class="companies-worked mr-5 w-2/12">
            <h2 class="text-3xl f-dark-blue font-extrabold dark:text-blue-500">
              4+
            </h2>
            <span class="text-sm f-gray dark:text-white">Companies Worked</span>
          </div> -->
        </div>
        <div class="resume pt-10">
          <button class="btn-accent flex items-center m-auto lg:m-0">
            <a
              href="https://drive.google.com/file/d/1j6_Ts7UhhVI8GWErHT-Ab8XMJIqKPHW8/view?usp=share_link"
              target="_blank"
            >
              Download CV&nbsp;
              <span
                ><font-awesome-icon
                  class="w-4"
                  :icon="['fas', 'arrow-circle-down']"
              /></span>
            </a>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
