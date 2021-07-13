<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16 mt-8">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight font-light">Hello! <span class="wave-hand">👋</span></div>
        <div class="text-orange-500 leading-loose">I'm Manikandan</div>
        <div class="leading-tight font-hairline">A Full stack web developer from Chennai, 🇮🇳 India.</div>
      </div>
      <div class="mt-8 sm:mt-0">
        <g-image src="../../static/developer.svg" alt="hero" width="280" class="mx-auto sm:mx-0" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">
        Welcome to my personal website, let me introduce a bit myself. I've a good knowledge in Vuejs and Laravel frameworks. I spend my days building web application for my organisation. My goal is to always build applications that are scalable and efficient under the hood while providing engaging, pixel-perfect user experiences.
      </p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/versionControl.svg" alt="browser" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/jsFramework.svg" alt="mobile" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div id="projects" style="position: relative; top: -40px; left: 0"/>
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl space-y-6">
          <li class="checkmark">
            <div>Coming Soon...</div>
            <div class="text-lg text-gray-600">Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui ab nam animi iure nemo exercitationem a, eius non culpa itaque!</div>
          </li>

        </ul>
      </div> <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div id="about" style="position: relative; top: -40px; left: 0"/>
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6">Get to know me:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div><g-image src="../../static/avatar.jpg" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">
            I'm a creative Web Developer from Chennai, India. I've a good knowledge in Vuejs and Laravel frameworks. I am constantly discovering new methods and technologies which help me learn more and more to provide exceptional work for the Web Development.
          </div>
        </div>

      </div> <!-- end get-to-know me -->
    </div>

    <div class="overflow-x-hidden">
      <div id="contact" style="position: relative; top: -40px; left: 0"/>
      <div class="contact-me bg-background-secondary pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>

          <p class="mb-12">
            Please feel free to send <a href="mailto:xqsit94@gmail.com">Email</a> to contact me about anything you want. You can also reach me on <a target="_blank" href="https://twitter.com/xqsit94">Twitter</a> with any feedback you have or if you just want to say 👋
          </p>

        </div>
      </div> <!-- end contact-me -->
    </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'xqsit94 | Creative Web Developer'
  }
}
</script>
