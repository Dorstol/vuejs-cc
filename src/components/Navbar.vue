<script setup>
import logo from '@/assets/img/logo.png'
</script>

<template>
  <nav class="bg-green-700 border-b border-green-500">
    <div class="px-2 mx-auto max-w-7xl sm:px-6 lg:px-8">
      <div class="flex justify-between items-center h-20">
        <div class="flex flex-1 justify-center items-center md:justify-start md:items-stretch">
          <!-- Logo -->
          <a
            class="flex flex-shrink-0 items-center mr-4"
            href="index.html"
          >
            <img
              class="w-auto h-10"
              :src="logo"
              alt="Vue Jobs"
            />
            <span class="hidden ml-2 text-2xl font-bold text-white md:block">Vue Jobs</span>
          </a>
          <div class="md:ml-auto">
            <div class="flex space-x-2">
              <a
                href="index.html"
                class="py-2 px-3 text-white bg-green-900 rounded-md hover:text-white hover:bg-gray-900"
              >Home</a>
              <a
                href="jobs.html"
                class="py-2 px-3 text-white rounded-md hover:text-white hover:bg-green-900"
              >Jobs</a>
              <a
                href="add-job.html"
                class="py-2 px-3 text-white rounded-md hover:text-white hover:bg-green-900"
              >Add
                Job</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>
