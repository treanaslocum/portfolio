<template>
  <div>
    <Header/>
    <main class="p-20 ml-64 w-2/3">
      <p class="text-4xl leading-normal">
        I'm a <span class="underline font-light">ui/ux designer,</span> <span class="underline font-light">full-stack developer,</span> and <span class="underline font-light">storyteller</span> that is passionate about building beautiful digital experiences. 
      </p>
      <p class="text-4xl mt-12 leading-normal">
        I also have a <span class="underline font-light">YouTube</span> channel where I share my personal experiences and spread inspiration and hope to other developers and designers.
      </p>
    </main>
    <section id="portfolio">
      <div class="flex items-center justify-center p-20">
        <div class="mr-12">
          <nuxt-link to="/hyperion">
            <img src="~assets/images/hyperion.jpg" alt="Hyperion" class="">
            <p class="mt-4 text-sm">UI/UX Design</p>
            <h3 class="text-2xl font-medium">Hyperion</h3>
          </nuxt-link>
          
        </div>
        <div>
          <nuxt-link to="/skillseed">
            <img src="~assets/images/skillseed.jpg" alt="Skillseed" class="">
            <p class="mt-4 text-sm">UI/UX Design, Web Development</p>
            <h3 class="text-2xl font-medium">Skillseed</h3>
          </nuxt-link>
          
        </div>
        
      </div>
      <div class="mt-16 flex items-center justify-center p-20">
        <div class="mr-12">
          <nuxt-link to="/podcastrs">
            <img src="~assets/images/podcastrs-home.png" alt="Podcastrs" class="">
            <p class="mt-4 text-sm">UI/UX Design</p>
            <h3 class="text-2xl font-medium">Podcastrs</h3>
          </nuxt-link>
          
        </div>
        <div>
          <img src="~assets/images/skillseed.jpg" alt="Hyperion" class="">
          <p class="mt-4 text-sm">UI/UX Design, Web Development</p>
          <h3 class="text-2xl font-medium">Skillseed</h3>
        </div>
        
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