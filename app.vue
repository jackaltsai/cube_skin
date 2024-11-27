<template>
  <div class="bg-color">
    <header class="absolute inset-x-0 top-0 z-50">
      <nav class="mx-auto flex max-w-7xl items-center justify-between p-6 lg:px-8" aria-label="Global">
        <div class="flex lg:flex-1">
          <a href="https://cube-skin.nuxt.dev" class="-m-1.5 p-1.5">
            <span class="sr-only">Cube skin</span>
            <img class="h-28 w-auto" src="/img/Cube_logo.png" alt="Cube skin" />
          </a>
        </div>
        <!-- <div class="flex lg:hidden">
          <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-gray-700" @click="mobileMenuOpen = true">
            <span class="sr-only">Open main menu</span>
            <Bars3Icon class="size-6" aria-hidden="true" />
          </button>
        </div> -->
        <!-- <div class="hidden lg:flex lg:gap-x-12">
          <a v-for="item in navigation" :key="item.name" :href="item.href" class="text-sm/6 font-semibold text-gray-900">{{ item.name }}</a>
        </div>
        <div class="hidden lg:flex lg:flex-1 lg:justify-end">
          <a href="#" class="text-sm/6 font-semibold text-gray-900">Log in <span aria-hidden="true">&rarr;</span></a>
        </div> -->
      </nav>
      <!-- <Dialog class="lg:hidden" @close="mobileMenuOpen = false" :open="mobileMenuOpen">
        <div class="fixed inset-0 z-50" />
        <DialogPanel class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10">
          <div class="flex items-center justify-between">
            <a href="#" class="-m-1.5 p-1.5">
              <span class="sr-only">Your Company</span>
              <img class="h-8 w-auto" src="https://tailwindui.com/plus/img/logos/mark.svg?color=indigo&shade=600" alt="" />
            </a>
            <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700" @click="mobileMenuOpen = false">
              <span class="sr-only">Close menu</span>
              <XMarkIcon class="size-6" aria-hidden="true" />
            </button>
          </div>
          <div class="mt-6 flow-root">
            <div class="-my-6 divide-y divide-gray-500/10">
              <div class="space-y-2 py-6">
                <a v-for="item in navigation" :key="item.name" :href="item.href" class="-mx-3 block rounded-lg px-3 py-2 text-base/7 font-semibold text-gray-900 hover:bg-gray-50">{{ item.name }}</a>
              </div>
              <div class="py-6">
                <a href="#" class="-mx-3 block rounded-lg px-3 py-2.5 text-base/7 font-semibold text-gray-900 hover:bg-gray-50">Log in</a>
              </div>
            </div>
          </div>
        </DialogPanel>
      </Dialog> -->
    </header>
    <main>
      <div class="relative isolate">
        <svg class="absolute inset-x-0 top-0 -z-10 h-[64rem] w-full stroke-gray-200 [mask-image:radial-gradient(32rem_32rem_at_center,white,transparent)]" aria-hidden="true">
          <defs>
            <pattern id="1f932ae7-37de-4c0a-a8b0-a6e3b4d44b84" width="200" height="200" x="50%" y="-1" patternUnits="userSpaceOnUse">
              <path d="M.5 200V.5H200" fill="none" />
            </pattern>
          </defs>
          <svg x="50%" y="-1" class="overflow-visible fill-gray-50">
            <path d="M-200 0h201v201h-201Z M600 0h201v201h-201Z M-400 600h201v201h-201Z M200 800h201v201h-201Z" stroke-width="0" />
          </svg>
          <rect width="100%" height="100%" stroke-width="0" fill="url(#1f932ae7-37de-4c0a-a8b0-a6e3b4d44b84)" />
        </svg>
        <div class="absolute left-1/2 right-0 top-0 -z-10 -ml-24 transform-gpu overflow-hidden blur-3xl lg:ml-24 xl:ml-48" aria-hidden="true">
          <div class="aspect-[801/1036] w-[50.0625rem] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30" style="clip-path: polygon(63.1% 29.5%, 100% 17.1%, 76.6% 3%, 48.4% 0%, 44.6% 4.7%, 54.5% 25.3%, 59.8% 49%, 55.2% 57.8%, 44.4% 57.2%, 27.8% 47.9%, 35.1% 81.5%, 0% 97.7%, 39.2% 100%, 35.2% 81.4%, 97.2% 52.8%, 63.1% 29.5%)" />
        </div>
        <div class="overflow-hidden">
          <div class="mx-auto max-w-7xl px-6 pb-32 pt-36 sm:pt-60 lg:px-8 lg:pt-32">
            <div class="mx-auto max-w-2xl gap-x-14 lg:mx-0 lg:flex lg:max-w-none lg:items-center">
              <div class="relative w-full lg:max-w-xl lg:shrink-0 xl:max-w-2xl">
                <h1 class="text-pretty text-5xl font-semibold tracking-tight text-gray-900 sm:text-7xl">專利a-GA液態飛梭·燈泡肌·負壓離子膜·斑密琳·韓式小氣泡</h1>
                <p class="mt-8 text-pretty text-lg font-medium text-gray-500 sm:max-w-md sm:text-xl/8 lg:max-w-none">📍板橋府中捷運站3號出口近林家花園</p>
                <p class="mt-8 text-pretty text-lg font-medium text-gray-500 sm:max-w-md sm:text-xl/8 lg:max-w-none">▫️韓國k-beauty 皮膚管理證書</p>
                <p class="mt-8 text-pretty text-lg font-medium text-gray-500 sm:max-w-md sm:text-xl/8 lg:max-w-none">▫️一人工作室，一人作業</p>
                <p class="mt-8 text-pretty text-lg font-medium text-gray-500 sm:max-w-md sm:text-xl/8 lg:max-w-none">▫️不推銷、美容至今已8年</p>
                <div class="flex gap-x-6">
                  <!-- <a v-for="item in navigation.social" :key="item.name" :href="item.href" class="text-gray-600 hover:text-gray-800">
                    <span class="sr-only">{{ item.name }}</span>
                    <component :is="item.icon" class="size-6" aria-hidden="true" />
                  </a> -->
                  <a href="https://www.instagram.com/p/C7OyAbJyZz3/">
                    <img class="h-10 w-auto"src="/img/instagram-fill.png" alt=""/>
                  </a>
                  <a href="https://lin.ee/fZw5twh">
                    <img class="h-10 w-auto"src="/img/line.png" alt=""/>
                  </a>
                  <a>
                    <img class="h-10 w-auto"src="/img/Cube_webproduct.png" alt=""/>
                  </a>
                </div>
                
              </div>
              <div class="mt-14 flex justify-end gap-8 sm:-mt-44 sm:justify-start sm:pl-20 lg:mt-0 lg:pl-0">
                <div class="ml-auto w-44 flex-none space-y-8 pt-32 sm:ml-0 sm:pt-80 lg:order-last lg:pt-36 xl:order-none xl:pt-80">
                  <div class="relative">
                    <img src="/img/p2.png" alt="" class="aspect-[2/3] w-full rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                    <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10" />
                  </div>
                </div>
                <div class="mr-auto w-44 flex-none space-y-8 sm:mr-0 sm:pt-52 lg:pt-36">
                  <div class="relative">
                    <img src="/img/p1.png" alt="" class="aspect-[2/3] w-full rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                    <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10" />
                  </div>
                  <div class="relative">
                    <img src="/img/p3.png" alt="" class="aspect-[2/3] w-full rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                    <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10" />
                  </div>
                </div>
                <div class="w-44 flex-none space-y-8 pt-32 sm:pt-0">
                  <div class="relative">
                    <CubeVideo></CubeVideo>
                  </div>
                  <div class="relative">
                    <img src="/img/p4.png" alt="" class="aspect-[2/3] w-full rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                    <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10" />
                  </div>
                  <div class="relative">
                    <img src="/img/p5.png" alt="" class="aspect-[2/3] w-full rounded-xl bg-gray-900/5 object-cover shadow-lg" />
                    <div class="pointer-events-none absolute inset-0 rounded-xl ring-1 ring-inset ring-gray-900/10" />
                  </div>
                  
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      
    </main>
    
    
    
    
  </div>
  
    
  <footer class="bg-color">
      <div class="mx-auto max-w-7xl px-6 py-12 md:flex md:items-center md:justify-between lg:px-8">
        
        <p class="mt-auto text-center text-sm/6 text-gray-600 md:order-1 md:mt-0">&copy; 2024 億辰科技有限公司. All rights reserved.</p>
      </div>
    </footer>
</template>

< setup>
import { ref } from 'vue'
import { Dialog, DialogPanel } from '@headlessui/vue'
import { Bars3Icon, XMarkIcon } from '@heroicons/vue/24/outline'

import { defineComponent, h } from 'vue'
  
const navigation = {
    social: [
      {
        name: 'Instagram',
        href: 'https://www.instagram.com/p/C7OyAbJyZz3/',
        icon: defineComponent({
          render: () =>
            h('svg', { fill: 'currentColor', viewBox: '0 0 24 24' }, [
              h('path', {
                'fill-rule': 'evenodd',
                d: 'M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z',
                'clip-rule': 'evenodd',
              }),
            ]),
        }),
      },
    ],
}

// const mobileMenuOpen = ref(false)
useHead({
  title: 'Cube Skin韓式肌膚管理',
  meta: [
    { 
      name: 'Cube Skin韓式肌膚管理',
      content: 'Cube Skin韓式肌膚管理'
    }
  ]
})


useSeoMeta({
  title: 'Cube Skin韓式肌膚管理',
  ogTitle: 'Cube Skin韓式肌膚管理',
  description: 'a-GA液態飛梭·燈泡肌·負壓離子膜·斑密琳·韓式小氣泡',
  ogDescription: 'a-GA液態飛梭·燈泡肌·負壓離子膜·斑密琳·韓式小氣泡',
  ogImage: 'https://cube-skin.nuxt.dev/img/p1.png',
  twitterCard: 'Cube Skin韓式肌膚管理',
})



</scrip>