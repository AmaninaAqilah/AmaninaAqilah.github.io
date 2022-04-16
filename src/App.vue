<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
<div class="bg-white">
  <div class="max-w-2xl mx-auto py-24 px-4 grid items-center grid-cols-1 gap-y-16 gap-x-8 sm:px-6 sm:py-32 lg:max-w-7xl lg:px-8 lg:grid-cols-2">
   <div>
      <img src="./assets/image.jpg" class="bg-gray-100 rounded-lg">
    </div>
    <div>
      <h2 class="text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl">Nur Amanina Aqilah</h2>
      <p class="mt-4 text-gray-500">Nur Amanina Aqilah, or Nina for short, is my name. I am now pursuing a Diploma in Web Development at Politeknik Brunei.</p>

      <dl class="mt-16 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 sm:gap-y-16 lg:gap-x-8 ">
        <div class="border-t border-gray-200 pt-4 ">
          <dt class="font-medium text-gray-900">Full name</dt>
          <dd class="mt-2 text-sm text-gray-500">Nur Amanina Aqilah</dd>
        </div>

        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Student ID</dt>
          <dd class="mt-2 text-sm text-gray-500">20FTT1456</dd>
        </div>

        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Email</dt>
          <dd class="mt-2 text-sm text-gray-500">20ftt1456@student.pb.edu.bn</dd>
        </div>

        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Interest</dt>
          <dd class="mt-2 text-sm text-gray-500">Reading and crime documentaries.</dd>
        </div>

        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Skills</dt>
          <dd class="mt-2 text-sm text-gray-500">Project Management, Leadership and negotiation</dd>
        </div>

        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Education</dt>
          <dd class="mt-2 text-sm text-gray-500">O-level and Diploma(currently)</dd>
        </div>
      </dl>
    </div>
   
  </div>
</div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
