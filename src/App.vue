<template>
  <main class="bg-gray-100">
    <div class="flex">
      <div class="px-6 py-12  mx-auto sm:max-w-2xl lg:px-12 py-24">
        <img class="h-12 sm:h-14" src="./assets/images/logo.svg" alt="Workcation Logo">
        <img class="mt-6 rounded-xl shadow-xl sm:mt-9 sm:h-80 sm:w-full sm:object-cover sm:object-center md:hidden"
             src="./assets/images/beach-work.jpg" alt="Woman is working on the beach">
        <h1 class="mt-6 text-3xl font-bold leading-tight tracking-tight text-gray-800 sm:text-3xl sm:leading-none md:mt-8 md:text-4xl">
          You can work from anywhere.
          <span class="inline-block mt-2 text-indigo-600">Take advantage of it.</span>
        </h1>
        <p class="mt-4 text-gray-500 tracking-normal leading-normal sm:mt-6 sm:text-xl sm:leading-8 sm:mt-6 lg:text-2xl lg:tracking-normal lg:leading-8">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet, animi dolorem incidunt ipsum iste labore
          laboriosam perferendis quos sapiente ullam vel, veniam vitae, voluptate. Aliquid distinctio dolore eos odit
          officiis.
        </p>
        <a href="#"
           class="btn btn-indigo">Book
          your
          escape</a>
        <a href="#"
           class="ml-3 btn btn-gray normal-case text-lg">Learn more</a>
      </div>
      <div class="hidden relative lg:block lg:w-1/2">
        <img class="inset-0 h-full object-cover object-center"
             src="./assets/images/beach-work.jpg" alt="Woman is working on the beach">
      </div>
    </div>
  </main>
</template>