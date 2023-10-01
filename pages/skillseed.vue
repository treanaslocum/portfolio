<template>
  <div>
    <Header/>

    

    <section class="mt-24">
      <div class="flex sm:flex-row flex-col  m-16">
        <div class="sm:w-2/4 w-full mr-16">
          <img class="mb-8" src="~/assets/images/skillseed.jpg">
          <img class="mb-8" src="~/assets/images/skillseed-hunting_topic.jpg">
          <img class="mb-8" src="~/assets/images/skillseed-topics.jpg">
        </div>
        <div class="sm:w-2/4 w-full">
          <h1 class="mb-8 text-5xl font-medium">Skillseed <br><span class="text-xl font-light">UI/UX Design, Web Development</span></h1>
          <a href="https://www.skillseed.app" target="_blank">https://www.skillseed.app</a>  
          <p class="mt-6 text-lg font-medium">Tools Used</p>
          <p class="mb-6">Nuxtjs, TailwindCSS, Adobe XD</p>
          
                  
        </div>
      </div>
    </section>


    <Footer/>
  </div>
</template>

<script setup>
useHead({
  title: 'Skillseed',
})
</script>