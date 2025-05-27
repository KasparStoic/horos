<template>
  <div>
    <section class="font-body">
      <div class="bg-black border rounded-xl border m-8 py-8 lg:py-16 mx-auto max-w-screen-md px-8">
          <div class="flex justify-center mb-8">
            <img src="/eye.jpg" alt="Eye" class="invert w-24 h-24" />
          </div>
          <p class="mb-8 lg:mb-16 font-light text-center text-gray-100 sm:text-xl">Uncover the truth and have clarity on your life's mysteries!</p>
          <!-- Astrology consultation information -->
          <div class="mb-8 lg:mb-12 text-gray-100 bg-gray-900/60 rounded-lg p-6 border border-gray-700">
            <h2 class="text-xl sm:text-2xl font-medium mb-4 text-center">Hindu & Western Astrology Consultation</h2>
            
            <p class="mb-4">Thank you for reaching out!</p>
            
            <p class="mb-4">I mainly specialise in Hindu astrology, but I also implement systems from Western astrology (Solar arc and secondary progressions). Both systems are complementary to each other.</p>
            
            <h3 class="text-lg font-medium mt-6 mb-3">What will you receive from the consultation?</h3>
            
            <p class="mb-4">A lot of people tend to ask me about the information being told to me by the astrological charts. The short answer is that there is no specific answer. Each chart is unique, considering the endlessness of variations. In some instances, a person's career and aspects of it is very clearly visible astrologically, in other instances, major problems related to love are clearer to the eye than their career and its details. Most of the time, the situations are variable and contain mixed conditions.</p>
            
            <p class="mb-4">In addition, astrology is not something I tend to bind with religion - In my analyses, I rely on practicality, and focus on what is clearly visible and what I can relate to based on my previous knowledge.</p>
            
            <div class="mt-6 bg-black/40 rounded p-4 border-l-4 border-primary-600">
              <ul class="list-disc pl-5 space-y-2">
                <li>Consultations are held via Skype or Zoom</li>
                <li>Length: approximately 1-1.5 hours</li>
                <li>Analysis includes: natal chart, dasha periods and upcoming transits</li>
              </ul>
            </div>
          </div>
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
          
          <!-- Footer links -->
          <div class="flex justify-center mt-8 text-xs text-gray-400 space-x-4">
            <p class="m-0">Leads managed by Choicism Investments OÜ</p>
            <span>|</span>
            <NuxtLink to="/privacy" class="hover:text-gray-200">Privacy Policy</NuxtLink>
            <span>|</span>
            <NuxtLink to="/terms" class="hover:text-gray-200">Terms of Service</NuxtLink>
          </div>
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