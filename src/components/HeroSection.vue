<template>
  <div
    class="flex h-screen-80 max-w-7xl m-center mt-24 md:flex-col lg:flex-row md:pt-10"
  >
    <div class="info flex flex-col items-start lg:w-3/6 m-auto">
      <h2
        data-aos="fade-right"
        data-aos-delay="500"
        data-aos-duration="500"
        class="text-5xl pb-3 font-extrabold f-black name dark:text-white duration-1000"
      >
        Charles Heculi.
      </h2>
      <h4
        class="text-lg pb-2 f-gray dark:text-white duration-1000"
        data-aos="fade-right"
        data-aos-delay="700"
        data-aos-duration="500"
      >
        Front End Developer
      </h4>
      <h5
        class="text-sm pb-12 f-gray dark:text-white duration-1000"
        data-aos="fade-right"
        data-aos-delay="800"
        data-aos-duration="500"
      >
        As a new front-end web developer, I am enthusiastic about learning and
        applying the latest technologies and techniques in web development. I
        have a strong foundation in HTML, CSS, and JavaScript, and I am
        continually expanding my knowledge through online courses and personal
        projects.
      </h5>
      <div data-aos="fade-right" data-aos-delay="800" data-aos-duration="700">
        <a
          class="btn-accent cursor-pointer flex items-center"
          href="mailto:heculicharles25@gmail.com"
        >
          <span> Contact Me&nbsp;</span>
          <span
            ><font-awesome-icon class="w-4" :icon="['fas', 'paper-plane']"
          /></span>
        </a>
      </div>
    </div>
    <div class="profile-image lg:w-full flex hidden md:flex md:m-auto md:pt-16">
      <img
        data-aos="zoom-in-right"
        data-aos-delay="1500"
        data-aos-duration="800"
        :class="`m-auto clipped light ismall img-first md:w-auto`"
        src="https://scontent.fmnl30-2.fna.fbcdn.net/v/t39.30808-6/308803395_3267481076873600_1295745097767619336_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=174925&_nc_ohc=RW1ezygK3LUAX_gfFOW&_nc_ht=scontent.fmnl30-2.fna&oh=00_AfCWV0thnn93BIdyriVfmibvzr-7Ir8rv1dm4qqFeDeaHQ&oe=6422FDC9"
        alt=""
        width="400"
      />
      <img
        data-aos="zoom-in-right"
        data-aos-delay="1700"
        data-aos-duration="800"
        class="m-auto clipped light imedium img-center md:w-auto"
        src="https://scontent.fmnl30-1.fna.fbcdn.net/v/t39.30808-6/241995752_2989142441374133_2545252136887198036_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=QvLvAgGPi3IAX_7bRvW&_nc_ht=scontent.fmnl30-1.fna&oh=00_AfB722r26iWgU0SeuULZjzrAH6gBw44xWH576oiRh9b47g&oe=64221975"
        alt=""
        width="400"
      />
      <img
        data-aos="zoom-in-right"
        data-aos-delay="1900"
        data-aos-duration="800"
        class="m-auto clipped light ismall img-last md:w-auto"
        src="https://scontent.fmnl30-1.fna.fbcdn.net/v/t39.30808-6/270503483_3070795859875457_7087532706747568297_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=174925&_nc_ohc=d9DrT11jwdUAX-4O0xA&_nc_ht=scontent.fmnl30-1.fna&oh=00_AfCYBxFzZ05m1U3SJt3pGxuZEwrRnkWHtj8_FfYwTNhugg&oe=642317B0"
        alt=""
        width="400"
      />
    </div>
  </div>
</template>

<script lang="ts" setup>
// import { watch } from "vue";
// import { useDark } from "@vueuse/core";
// const isDark = useDark();
</script>
<style lang="scss" scoped>
.clipped {
  clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%);
}
.ismall {
  height: 19rem;
}
.imedium {
  height: 25rem;
}

.img-first {
  margin-left: 12px;
  height: 350px;
  clip-path: polygon(25% 0%, 100.5% 0%, 73% 100%, 0% 100%);
}

.img-center {
  margin-left: -66px;
}

.img-last {
  margin-left: -65px;
}

.light {
  filter: grayscale(40%);
  transition: 0.5s ease-out 100ms;
  cursor: pointer;

  &:hover {
    filter: grayscale(0);
    transform: scale(1.03);
    z-index: 999;
  }

  &.colored {
    filter: grayscale(0) !important;
  }
}

.profile-image {
  &::after {
    content: "";
    position: absolute;
    bottom: 120px;
    background: rgba(80, 80, 80, 0.503);
    width: 25rem;
    height: 50px;
    border-radius: 50%;
    filter: blur(20px);
    margin-left: 6rem;
  }
}
</style>
