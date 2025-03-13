<template>
  <div>
    <section class="font-body">
      <div class="bg-black border rounded-xl border m-8 py-8 lg:py-16 mx-auto max-w-screen-md px-8">
          <div class="flex justify-center mb-8">
            <img src="/eye.jpg" alt="Eye" class="invert w-24 h-24" />
          </div>
          <p class="mb-8 lg:mb-16 font-light text-center text-gray-100 sm:text-xl">Uncover the truth and have clarity on your life's mysteries!</p>
          <form action="https://formspree.io/f/maneygbl" method="POST" class="space-y-8">
              <div class="w-full">
                  <label for="email" class="block mb-2 text-sm font-medium text-gray-100">Your email</label>
                  <input name="email" type="email" id="email" class="shadow-sm bg-gray-900 border border-gray-300 text-gray-100 text-sm rounded-lg focus:ring-primary-500 focus:border-primary-500 block w-full -ml-2.5 p-2.5 " placeholder="name@example.com" required>
              </div>
              <div class="sm:col-span-2">
                  <label for="message" class="block mb-2 text-sm font-medium text-gray-100">Your message</label>
                  <textarea name="message" id="message" rows="6" class="font-sans block -ml-2.5 p-2.5 w-full text-sm text-gray-100 bg-gray-900 rounded-lg shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-500" placeholder="Any comments?"></textarea>
              </div>
              <button type="submit" class="py-3 -ml-3 px-5 text-sm font-medium text-center text-gray-100 rounded-lg border border-gray-900 bg-primary-900 sm:w-fit hover:bg-primary-800">Send message</button>
          </form>
      </div>
    </section>
  </div>
</template>

<style>
html {
  min-height: 100vh;
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('/stars.jpeg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  margin: 0;
  padding: 0;
}
</style>