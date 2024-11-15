<template>
    <section data-layername="heroSection" class="flex overflow-hidden relative gap-10 items-start px-20 py-16 max-md:px-5">
      <nav class="flex absolute bottom-8 left-28 z-0 gap-8 items-start py-1 min-w-[240px]">
        <button data-layername="button" class="flex gap-2 justify-center items-center px-4 w-14 h-14 bg-black rounded min-h-[56px]" aria-label="Social Media Button 1">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/936121b51a1bc9a1cc57d78e9626474a77886cc2779273721f7982ebb7632f98?placeholderIfAbsent=true&apiKey=7f2d6e619c424500882c60f5d3f5aafb" alt="" class="object-contain self-stretch my-auto w-5 aspect-square" />
        </button>
        <button data-layername="button" class="flex gap-2 justify-center items-center px-4 w-14 h-14 rounded border-2 border-black border-solid min-h-[56px]" aria-label="Social Media Button 2">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/79b5ec9aa45b3144a55830fde4021401799429d7dfb2a59d256c022cb1d1f80a?placeholderIfAbsent=true&apiKey=7f2d6e619c424500882c60f5d3f5aafb" alt="" class="object-contain self-stretch my-auto w-5 aspect-square" />
        </button>
        <button data-layername="button" class="flex gap-2 justify-center items-center px-4 w-14 h-14 rounded border-2 border-black border-solid min-h-[56px]" aria-label="Social Media Button 3">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/a739775e5241009c23bc186390010659461f9e274a30592fff45523945b00ab0?placeholderIfAbsent=true&apiKey=7f2d6e619c424500882c60f5d3f5aafb" alt="" class="object-contain self-stretch my-auto w-5 aspect-square" />
        </button>
        <button data-layername="button" class="flex gap-2 justify-center items-center px-4 w-14 h-14 rounded border-2 border-black border-solid min-h-[56px]" aria-label="Social Media Button 4">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/a891527ae63676237fbf17edd9ac65cf5ef7a6ad7c3c8c8e8707d47e5789d1a1?placeholderIfAbsent=true&apiKey=7f2d6e619c424500882c60f5d3f5aafb" alt="" class="object-contain self-stretch my-auto w-5 aspect-square" />
        </button>
      </nav>
      <div data-layername="container" class="flex overflow-hidden z-0 justify-between items-center px-8 min-w-[240px] w-[1280px] max-md:px-5 max-md:max-w-full">
        <article data-layername="banner" class="flex overflow-hidden flex-col justify-center self-stretch py-5 my-auto min-w-[240px] w-[600px] max-md:max-w-full">
          <div class="flex flex-col w-full max-md:max-w-full">
            <header class="flex flex-col items-start w-full text-5xl tracking-tighter leading-none max-md:max-w-full max-md:text-4xl">
              <h1 class="flex gap-4 items-start text-black max-md:max-w-full max-md:text-4xl">
                <span data-layername="helloIam" class="max-md:text-4xl">Hello I'm</span>
                <span data-layername="irfanFalih" class="font-extrabold max-md:text-4xl">Irfan Falih</span>
              </h1>
              <div class="flex flex-wrap gap-4 items-start mt-5 font-extrabold whitespace-nowrap max-md:max-w-full max-md:text-4xl">
                <span data-layername="frontend" class="text-black max-md:text-4xl">Frontend</span>
                <span data-layername="developer" class="border-black border-solid border-[3px] max-md:text-4xl">Developer</span>
              </div>
              <div class="flex gap-4 items-start mt-5 text-black max-md:max-w-full max-md:text-4xl">
                <span data-layername="basedIn" class="max-md:text-4xl">Based In</span>
                <span data-layername="indonesia" class="font-extrabold max-md:text-4xl">Indonesia.</span>
              </div>
            </header>
            <p data-layername="committedToDeliveringUserFriendlySolutionsIPossessTheSkillsToBlendDesignAndTechnologyEnhancingUserExperiencesAndSupportingBusinessGoals" class="mt-8 text-base tracking-wide leading-6 text-zinc-500 max-md:max-w-full">
              Committed to delivering user-friendly solutions, I possess the skills to blend design and technology, enhancing user experiences and supporting business goals.
            </p>
          </div>
        </article>
        <aside data-layername="banner" class="flex self-stretch my-auto min-h-[596px] min-w-[240px] max-md:max-w-full"></aside>
      </div>
    </section>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue'
  
  export default defineComponent({
    name: 'HeroSection',
  })
  </script>