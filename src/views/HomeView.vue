<template>
   <div class="container mx-auto">
    <div class="mt-10">
        <div class="flex items-center justify-center space-x-4">
          <div class="grid grid-cols-3 gap-4">
            <router-link :to="{ name: 'bus.index' }" class="shadow-sm hover:shadow-md bg-white border-2 text-gray-900 px-14 py-6 rounded-md text-sm font-medium text-center">
              <img src="img/003.png" alt="" class="h-10 mb-2 mx-auto opacity-75">
              <span class="text-xl font-semibold">BUS</span>
            </router-link>
            <router-link :to="{ name: 'supir.index' }" class="shadow-sm hover:shadow-md bg-white border-2 text-gray-900 px-14 py-6 rounded-md text-sm font-medium text-center">
              <img src="img/006.png" alt="" class="h-10 mb-2 mx-auto opacity-75">
              <span class="text-xl font-semibold">SUPIR</span>
            </router-link>
            <router-link :to="{ name: 'jadwal.index' }" class="shadow-sm hover:shadow-md bg-white border-2 text-gray-900 px-14 py-6 rounded-md text-sm font-medium text-center">
              <img src="img/005.png" alt="" class="h-10 mb-2 mx-auto opacity-75">
              <span class="text-xl font-semibold">JADWAL</span>
            </router-link>
            <router-link :to="{name: 'rute.index'}" class="shadow-sm hover:shadow-md bg-white border-2 text-gray-900 px-14 py-6 rounded-md text-sm font-medium text-center">
              <img src="img/004.png" alt="" class="h-10 mb-2 mx-auto opacity-75">
              <span class="text-xl font-semibold">RUTE</span>
            </router-link>
            <router-link :to="{ name: 'terminal.index' }" class="shadow-sm hover:shadow-md bg-white border-2 text-gray-900 px-14 py-6 rounded-md text-sm font-medium text-center">
              <img src="img/003.png" alt="" class="h-10 mb-2 mx-auto opacity-75">
              <span class="text-xl font-semibold">TERMINAL</span>
            </router-link>
          </div>
        </div>
    </div>
  </div>
</template>

