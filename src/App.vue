<template>
  <app>
    <header class="text-gray-700 body-font bg-teal-500">
      <nav fixed-top class="flex items-center justify-between flex-wrap bg-green-500 p-6">
        <div class="flex items-center flex-shrink-0 text-white mr-6">
          <span class="font-semibold text-xl tracking-tight">Plug and Plant</span>
        </div>
        <div class="block lg:hidden">
          <button
            class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
            <svg
              class="fill-current h-3 w-3"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg">
              <title>Menu</title>
              <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
            </svg>
          </button>
        </div>
        <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto md:ml-auto">
          <div class="text-sm lg:flex-grow">
            <a
              href="#responsive-header"
              class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4"
            >About Us</a>
            <a
              href="#responsive-header"
              class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4"
            >Feature</a>
            <a
              href="#responsive-header"
              class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white"
            >Contact Us</a>
          </div>
        </div>
      </nav>
    </header>

    <section class="text-gray-500 bg-gray-900 body-font">
      <div class="container px-5 py-24 mx-auto flex flex-col">
        <div class="lg:w-4/6 mx-auto">
          <div class="flex flex-col sm:flex-row mt-10">
            <div class="sm:w-1/3 text-center sm:pr-8 sm:py-8">
              <div
                class="w-40 h-40 inline-flex items-center justify-center mt-5"
                style="margin-top:90px;"
              >
                <img src="../src/assets/ss_mobile/1.png" alt srcset />
              </div>
            </div>
            <div
              class="sm:w-2/3 sm:pl-8 sm:py-8 sm:border-l border-gray-800 sm:border-t-0 border-t mt-4 pt-4 sm:mt-0 text-center sm:text-left"
            >
              <h1 class="text-6xl">Plug And Plant</h1>
              <p class="text-2xl">Apps to help you to take care your plant easily</p>
              <p class="text-2xl">Give You some that help you to resolve yhe problems of your plant</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="text-gray-500 bg-gray-900 body-font">
      <div class="container px-5 py-24 mx-auto">
        <div class="flex flex-col text-center w-full mb-20" style="margin-bottom:120px;">
          <h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-white">Daily Reports</h1>
          <p
            class="lg:w-2/3 mx-auto leading-relaxed text-base"
          >In this screen you can see the reports of your daily planting and you can easily know. what kind of enviroment that make some your plant delayed in watering</p>
        </div>
        <div class="flex flex-wrap -m-4 mt-5 ml-5" style="margin-left:120px;">
          <div class="lg:w-1/3 sm:w-1/2 p-4">
            <div class="flex relative">
              <div class="w-40 h-40 inline-flex items-center justify-center">
                <img class="object-center w-50 h-50" src="../src/assets/ss_mobile/2.png" />
              </div>
            </div>
          </div>
          <div class="lg:w-1/3 sm:w-1/2 p-4">
            <div class="flex relative">
              <div class="w-40 h-40 inline-flex items-center justify-center">
                <img src="../src/assets/ss_mobile/3.png" alt srcset />
              </div>
            </div>
          </div>
          <div class="lg:w-1/3 sm:w-1/2 p-4">
            <div class="flex relative">
              <div class="w-40 h-40 inline-flex items-center justify-center">
                <img src="../src/assets/ss_mobile/3_2.png" alt srcset />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="text-gray-500 bg-gray-900 body-font relative">
      <div class="container px-5 py-24 mx-auto">
        <div class="flex flex-col text-center w-full mb-12">
          <h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-white">Contact Us</h1>
          <p class="lg:w-2/3 mx-auto leading-relaxed text-base">
            Questions, consultations, discussions or just getting acquainted,
            <br />please contact the number below. We will try
            provide the best solution.
          </p>
        </div>
        <div class="lg:w-1/2 md:w-2/3 mx-auto">
          <div class="flex flex-wrap -m-2">
            <div class="p-2 w-1/2">
              <input
                class="w-full bg-gray-800 rounded border border-gray-700 text-white focus:outline-none focus:border-blue-500 text-base px-4 py-2"
                placeholder="Name"
                type="text"
              />
            </div>
            <div class="p-2 w-1/2">
              <input
                class="w-full bg-gray-800 rounded border border-gray-700 text-white focus:outline-none focus:border-blue-500 text-base px-4 py-2"
                placeholder="Email"
                type="email"
              />
            </div>
            <div class="p-2 w-full">
              <textarea
                class="w-full bg-gray-800 rounded border border-gray-700 text-white focus:outline-none h-48 focus:border-blue-500 text-base px-4 py-2 resize-none block"
                placeholder="Message"
              ></textarea>
            </div>
            <div class="p-2 w-full">
              <button
                class="flex mx-auto text-white bg-blue-500 border-0 py-2 px-8 focus:outline-none hover:bg-blue-600 rounded text-lg"
              >Send</button>
            </div>
            <div class="p-2 w-full pt-8 mt-8 border-t border-gray-800 text-center">
              <a class="text-blue-500">PluginTegal@gmail.com</a>
              <p class="leading-normal my-5">
                Perumahan Ndalem Parikesit
                <br />Block B NO. 7
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <footer class="text-gray-500 bg-gray-900 body-font">
      <div class="container px-5 py-8 mx-auto flex items-center sm:flex-row flex-col">
        <a
          class="flex title-font font-medium items-center md:justify-start justify-center text-white"
        >
          <span class="ml-3 text-xl">Plug And Plant</span>
        </a>
        <p
          class="text-sm text-gray-600 sm:ml-4 sm:pl-4 sm:border-l-2 sm:border-gray-800 sm:py-2 sm:mt-0 mt-4"
        >
          © 2020 Plugin —
          <a
            href="https://twitter.com/knyttneve"
            class="text-gray-500 ml-1"
            target="_blank"
            rel="noopener noreferrer"
          >@officialPlugin</a>
        </p>
        <span class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start">
          <a class="text-gray-600">
            <svg
              fill="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="w-5 h-5"
              viewBox="0 0 24 24"
            >
              <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z" />
            </svg>
          </a>
          <a class="ml-3 text-gray-600">
            <svg
              fill="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="w-5 h-5"
              viewBox="0 0 24 24"
            >
              <path
                d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"
              />
            </svg>
          </a>
          <a class="ml-3 text-gray-600">
            <svg
              fill="none"
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="w-5 h-5"
              viewBox="0 0 24 24"
            >
              <rect width="20" height="20" x="2" y="2" rx="5" ry="5" />
              <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01" />
            </svg>
          </a>
          <a class="ml-3 text-gray-600">
            <svg
              fill="currentColor"
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="0"
              class="w-5 h-5"
              viewBox="0 0 24 24"
            >
              <path
                stroke="none"
                d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"
              />
              <circle cx="4" cy="4" r="2" stroke="none" />
            </svg>
          </a>
        </span>
      </div>
    </footer>
  </app>
</template>

<script>
export default {};
</script>

<style>
</style>