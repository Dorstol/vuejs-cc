<script setup>
import logo from '@/assets/img/logo.png';
import { RouterLink } from 'vue-router';
</script>

<template>
  <nav class="bg-green-700 border-b border-green-500">
    <div class="px-2 mx-auto max-w-7xl sm:px-6 lg:px-8">
      <div class="flex justify-between items-center h-20">
        <div class="flex flex-1 justify-center items-center md:justify-start md:items-stretch">
          <!-- Logo -->
          <RouterLink class="flex flex-shrink-0 items-center mr-4" to="/">
            <img class="w-auto h-10" :src="logo" alt="Vue Jobs" />
            <span class="hidden ml-2 text-2xl font-bold text-white md:block">Vue Jobs</span>
          </RouterLink>
          <div class="md:ml-auto">
            <div class="flex space-x-2">
              <RouterLink to="/"
                class="py-2 px-3 text-white bg-green-900 rounded-md hover:text-white hover:bg-gray-900">Home
              </RouterLink>
              <RouterLink to="/jobs" class="py-2 px-3 text-white rounded-md hover:text-white hover:bg-green-900">Jobs
              </RouterLink>
              <RouterLink to="/job/add" class="py-2 px-3 text-white rounded-md hover:text-white hover:bg-green-900">
                Add
                Job</RouterLink>
            </div>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>
