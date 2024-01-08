<template>
  <div class="p-6 max-w-sm mx-auto bg-white rounded-xl shadow-md flex items-center space-x-4 mt-10">
    <div class="flex-shrink-0">
      <img class="h-12 w-12" src="../assets/vue.svg" alt="ChitChat Logo" />
    </div>
    <div>
      <div class="text-xl font-medium text-black">ChitChat</div>
      <p class="text-gray-500">You have a new message!</p>
    </div>
  </div>

  <div class="py-8 px-8 max-w-sm mx-auto bg-white rounded-xl shadow-md space-y-2 sm:py-4 sm:flex sm:items-center sm:space-y-0 sm:space-x-6 mt-10">
    <img class="block mx-auto h-24 rounded-full sm:mx-0 sm:flex-shrink-0" src="../assets/vue.svg" alt="Woman's Face" />
    <div class="text-center space-y-2 sm:text-left">
      <div class="space-y-0.5">
        <p class="text-lg text-black font-semibold">Erin Lindford</p>
        <p class="text-gray-500 font-medium">Product Engineer</p>
      </div>
      <button class="px-4 py-1 text-sm text-purple-600 font-semibold rounded-full border border-purple-200 hover:text-white hover:bg-purple-600 hover:border-transparent focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-offset-2">Message</button>

      <primaryButton>Click me!</primaryButton>
      <button class="btn btn-purple">Click me</button>
    </div>
  </div>

  <div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl mt-10">
    <div class="md:flex">
      <div class="md:flex-shrink-0">
        <img class="h-48 w-full object-cover md:h-full md:w-48" src="../assets/vue.svg" alt="Man looking at item at a store" />
      </div>
      <div class="p-8">
        <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Case study</div>
        <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Finding customers for your new business</a>
        <p class="mt-2 text-gray-500">Getting a new business off the ground is a lot of hard work. Here are five ideas you can use to find your first customers.</p>
      </div>
    </div>
  </div>

  <form class="flex max-w-sm mx-auto mt-10">
    <input class="border focus:outline-none focus:ring-2 focus:ring-purple-600 focus:border-transparent bg-white p-2 rounded-md mr-2" />
    <button class="btn btn-purple">Sign up</button>
  </form>

  <div class="group border-indigo-500 hover:bg-white hover:border-indigo-300 rounded-lg border bg-white p-4 mt-10 max-w-sm mx-auto">
    <p class="text-indigo-600 group-hover:text-gray-900 font-semibold">Get started</p>
    <p class="text-indigo-500 group-hover:text-gray-500 font-semibold text-sm">Learn more about our products</p>
  </div>

  <div class="max-w-sm mx-auto">
    <button class="group bg-yellow-500 focus:bg-yellow-600 hover:bg-yellow-600 focus:outline-none focus:ring-2 focus:ring-yellow-600 focus:ring-offset-2 text-white font-semibold py-2 px-4 rounded inline-flex items-center mt-10">
      <svg class="text-white group-focus:text-yellow-300 mr-2" width="12" height="20" fill="currentColor">
        <path d="M2 20 L12 10 L2 0 Z"></path>
      </svg>
      Bookmark
    </button>
  </div>

  <div class="max-w-sm mx-auto mt-10">
    <div class="text-gray-400 focus-within:text-gray-950 relative">
      <div class="absolute inset-y-0 left-0 flex items-center pl-2">
        <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none">
          <!-- 邮件 -->
          <path d="M22 4H2C0.9 4 0 4.9 0 6V18C0 19.1 0.9 20 2 20H22C23.1 20 24 19.1 24 18V6C24 4.9 23.1 4 22 4ZM22 18H2V8L12 13L22 8V18Z" fill="currentColor" />
        </svg>
      </div>
      <input class="focus:ring-2 focus:ring-gray-300 focus:border-transparent block w-full pl-10 sm:text-sm border-gray-300 rounded-md border p-2" />
    </div>

    <div>
      <button class="focus:ring-2 focus:ring-red-500 focus:outline-none focus:ring-offset-2 bg-red-500 hover:bg-red-600 text-white font-semibold py-2 px-4 rounded inline-flex items-center mt-10">Ring on focus</button>
    </div>
    <div>
      <button class="focus:outline-none focus-visible:ring-2 focus-visible:ring-rose-500 focus-visible:ring-offset-2 bg-rose-500 hover:bg-rose-600 text-white font-semibold py-2 px-4 rounded inline-flex items-center mt-10">Ring on focus-visible</button>
    </div>

    <div>
      <button class="transform motion-safe:hover:animate-spin motion-reduce:transform-none bg-purple-500 hover:bg-purple-600 text-white font-semibold py-2 px-4 rounded inline-flex items-center mt-10">Hover scale</button>
    </div>

    <div>
      <button class="disabled:opacity-50 bg-purple-500 hover:bg-purple-600 text-white font-semibold py-2 px-4 rounded inline-flex items-center mt-10" disabled>Disabled</button>
    </div>

    <div class="rounded-t-xl overflow-hidden bg-slate-100 p-10">
      <div class="mt-10 p-4 max-w-xs mx-auto bg-white rounded-xl shadow-md">
        <label for="" class="flex items-center space-x-3">
          <input type="checkbox" name="checked-demo" value="1" class="before:content[''] peer relative h-5 w-5 cursor-pointer rounded-md border border-blue-gray-200 transition-all before:absolute before:top-2/4 before:left-2/4 before:block before:h-12 before:w-12 before:-translate-y-2/4 before:-translate-x-2/4 before:rounded-full before:bg-blue-gray-500 before:opacity-0 before:transition-opacity checked:border-blue-500 checked:bg-blue-500 checked:before:bg-blue-500 hover:before:opacity-10" />
          <span class="text-gray-900 font-medium">Checkbox</span>
        </label>
      </div>
    </div>

    <button type="button" class="py-4 px-6 bg-pink-600 hover:bg-pink-700 focus:ring-pink-500 focus:ring-offset-pink-200 text-white w-full transition ease-in duration-200 text-center text-base font-semibold shadow-md focus:outline-none focus:ring-2 focus:ring-offset-2">Fat is me</button>

    <button class="bg-emerald-500 text-white active:bg-emerald-600 font-bold uppercase text-xs px-4 py-2 rounded shadow hover:shadow-md outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150" type="button">Small</button>

    <button type="button" data-ripple-light="true" class="align-middle select-none font-sans font-bold text-center uppercase transition-all disabled:opacity-50 disabled:shadow-none disabled:pointer-events-none text-xs py-3 px-6 rounded-lg bg-gray-900 text-white shadow-md shadow-gray-900/10 hover:shadow-lg hover:shadow-gray-900/20 focus:opacity-[0.85] focus:shadow-none active:opacity-[0.85] active:shadow-none">Button</button>

    <div role="alert" class="relative block w-full px-4 py-4 text-base text-white bg-gray-900 rounded-lg font-regular" style="opacity: 1">
      <div class="mr-12">A simple alert for showing message.</div>
    </div>

    <div class="grid min-h-[140px] w-full place-items-center overflow-x-scroll rounded-lg p-6 lg:overflow-visible">
      <figure class="relative w-full h-96">
        <img class="object-cover object-center w-full h-full rounded-xl" src="https://images.unsplash.com/photo-1682407186023-12c70a4a35e0?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=2832&amp;q=80" alt="nature image" />
        <figcaption class="absolute bottom-8 left-2/4 flex w-[calc(100%-4rem)] -translate-x-2/4 justify-between rounded-xl border border-white bg-white/75 py-4 px-6 shadow-lg shadow-black/5 saturate-200 backdrop-blur-sm">
          <div>
            <h5 class="block font-sans text-xl antialiased font-semibold leading-snug tracking-normal text-blue-gray-900">Sara Lamalo</h5>
            <p class="block mt-2 font-sans text-base antialiased font-normal leading-relaxed text-gray-700">20 July 2022</p>
          </div>
          <h5 class="block font-sans text-xl antialiased font-semibold leading-snug tracking-normal text-blue-gray-900">Growth</h5>
        </figcaption>
      </figure>
    </div>

    <video className="h-full w-full rounded-lg" controls>
      <source src="https://docs.material-tailwind.com/demo.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>

    <button class="align-middle select-none font-sans font-bold text-center uppercase transition-all disabled:opacity-50 disabled:shadow-none disabled:pointer-events-none text-xs py-3 px-6 rounded-lg bg-gray-900 text-white shadow-md shadow-gray-900/10 hover:shadow-lg hover:shadow-gray-900/20 focus:opacity-[0.85] focus:shadow-none active:opacity-[0.85] active:shadow-none" type="button" data-ripple-light="true">Ripple Effect On</button>
    <button class="align-middle select-none font-sans font-bold text-center uppercase transition-all disabled:opacity-50 disabled:shadow-none disabled:pointer-events-none text-xs py-3 px-6 rounded-lg bg-gray-900 text-white shadow-md shadow-gray-900/10 hover:shadow-lg hover:shadow-gray-900/20 focus:opacity-[0.85] focus:shadow-none active:opacity-[0.85] active:shadow-none" type="button" data-ripple-light="false">Ripple Effect Off</button>
  </div>
</template>

<script>
import primaryButton from '@/components/PrimaryButton.vue'

export default {
  name: 'Home',
  components: {
    primaryButton,
  },
}
</script>

<style></style>
