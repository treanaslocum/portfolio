<template>
  <div>
    <Header/>
    <main class="p-20 lg:ml-20 lg:w-3/4 sm:w-2/5 md:w-5/6">
      <p class="lg:text-4xl sm:text-2xl leading-normal">
        I'm a <span class="underline font-light">ui/ux designer,</span> <span class="underline font-light">frontend developer,</span> and <span class="underline font-light">storyteller</span> that is passionate about building beautiful digital experiences. 
      </p>
      <p class="lg:text-4xl sm:text-2xl mt-12 leading-normal">
        I also have a <span class="underline font-light">YouTube</span> channel where I share my personal experiences and spread inspiration and hope to other developers and designers.
      </p>
    </main>
    <section id="portfolio">
      <div class="lg:p-20 flex flex-col justify-center">
        <div class="">
          <nuxt-link to="/hyperion">
            <img src="~assets/images/hyperion.jpg" alt="Hyperion" class="">
            <p class="mt-4 lg:text-sm sm:text-xs">UI/UX Design</p>
            <h3 class="lg:text-2xl sm:text-xl font-medium">Hyperion</h3>
          </nuxt-link>
          
        </div>
        <div class="mt-20">
          <nuxt-link to="/skillseed">
            <img src="~assets/images/skillseed.jpg" alt="Skillseed" class="">
            <p class="mt-4 lg:text-sm sm:text-xs">UI/UX Design, Web Development</p>
            <h3 class="lg:text-2xl sm:text-xl font-medium">Skillseed</h3>
          </nuxt-link>
          
        </div>
        
      </div>
      <div class="mt-16 lg:p-20 flex flex-col justify-center">
        <div class="">
          <nuxt-link to="/podcastrs">
            <img src="~assets/images/podcastrs-home.png" alt="Podcastrs" class="">
            <p class="mt-4 lg:text-sm sm:text-xs">UI/UX Design</p>
            <h3 class="lg:text-2xl sm:text-xl font-medium">Podcastrs</h3>
          </nuxt-link>
          
        </div>
        <nuxt-link to="/motion">
          <div class="mt-20 mb-20">
            <img src="~assets/images/motion.png" alt="Motion" class="">
            <p class="mt-4 lg:text-sm sm:text-xs">UI/UX Design</p>
            <h3 class="lg:text-2xl m:text-xl font-medium">Motion</h3>
          </div>
      </nuxt-link>
        
      </div>
    </section>
  </div>
</template>

<script setup>
useHead({
  title: 'Treana Slocum, ui/ux designer, full-stack developer, storyteller',
  meta: [
    { name: 'description', content: "Treana Slocum's portfolio" }
  ],
})
</script>