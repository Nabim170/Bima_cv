<template>
    <div>
      <nav class="bg-gray-800 p-4">
        <div class="container mx-auto flex justify-between">
          <a href="/" class="text-white text-lg font-semibold">Nanda Bima Pratama</a>
          <div>
            <nuxt-link to="/" class="text-white mx-2">Home</nuxt-link>
            <nuxt-link to="/projects" class="text-white mx-2">Projects</nuxt-link>
            <nuxt-link to="/skills" class="text-white mx-2">Skills</nuxt-link>
            <nuxt-link to="/contact" class="text-white mx-2">Contact</nuxt-link>
          </div>
        </div>
      </nav>
      <nuxt />
    </div>
  </template>
  
  <style>
  nav a {
    transition: color 0.3s ease;
  }
  nav a:hover {
    color: #f0f0f0;
  }
  </style>
  