---
layout: default
---

<header class="bg-gradient-to-r from-blue-600 to-teal-500 text-white">
  <div class="container mx-auto px-4 md:px-8">
    <div class="flex flex-col md:flex-row items-center justify-between max-h-[150px]">
      <div class="md:w-1/2 mb-8 md:mb-0">
        <h1 class="text-5xl md:text-6xl font-bold mb-4">Navigate with Confidence</h1>
        <p class="text-lg mb-6">Truewind, your essential Canadian marine weather companion for safe and reliable voyages.</p>
      </div>
      <div class="md:w-1/2 pb-20 h-[200px]">
        <img src="/assets/appscreen.jpg" alt="Truewind Canadian Marine Weather App Screenshot" class="appscreen rounded-lg shadow-lg">
      </div>
    </div>
  </div>
</header>



<section class="bg-gradient-to-r from-blue-500 via-teal-500 to-blue-500 text-white py-12 md:py-20">
  <div class="container mx-auto px-4 md:px-8">
    <h2 class="text-3xl md:text-4xl font-bold mb-8">Key Features</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div>
        <h3 class="text-xl font-bold mb-4">Official Canadian Data</h3>
        <p>Reliable, up-to-date marine weather information sourced directly from Canadian authorities.</p>
      </div>
      <div>
        <h3 class="text-xl font-bold mb-4">Offline Accessibility</h3>
        <p>Access essential weather data even in remote locations with our offline mode.</p>
      </div>
      <div>
        <h3 class="text-xl font-bold mb-4">Customizable Maps</h3>
        <p>Navigate Canadian waters with ease using our intuitive and customizable map interface.</p>
      </div>
      <div>
        <h3 class="text-xl font-bold mb-4">Real-Time Updates</h3>
        <p>Get the latest weather information to plan your voyages with confidence.</p>
      </div>
      <div>
        <h3 class="text-xl font-bold mb-4">Weather Alerts</h3>
        <p>Receive timely notifications to stay ahead of changing conditions on the water.</p>
      </div>
      <div>
        <h3 class="text-xl font-bold mb-4">Favorite Locations</h3>
        <p>Save your most frequently visited spots for quick access and trip planning.</p>
      </div>
    </div>
  </div>
</section>

<section class="bg-gradient-to-r from-blue-400 to-cyan-400 text-white py-12 md:py-20">
  <div class="container mx-auto px-4 md:px-8">
    <h2 class="text-3xl md:text-4xl font-bold mb-8">Trusted by Canadian Mariners</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <div>
        <blockquote class="bg-white rounded-lg p-6 shadow-lg text-gray-900">
          <p class="text-lg font-medium">"Truewind is a game-changer for my sailing trips. The offline weather data and customizable maps are invaluable."</p>
          <footer class="mt-4">
            <div class="flex items-center space-x-4">
              <!-- <img src="/assets/user-avatar.jpg" alt="User Avatar" class="w-10 h-10 rounded-full"> -->
              <div>
                <div class="font-medium">Sarah Wilson</div>
                <div class="text-gray-500">Avid Sailor, Ontario</div>
              </div>
            </div>
          </footer>
        </blockquote>
      </div>
      <div>
        <blockquote class="bg-white rounded-lg p-6 shadow-lg text-gray-900">
          <p class="text-lg font-medium">"As a Canadian fisherman, I rely on Truewind to keep me safe and informed on the water. The app is a must-have."</p>
          <footer class="mt-4">
            <div class="flex items-center space-x-4">
              <!-- <img src="/assets/user-avatar-2.jpg" alt="User Avatar" class="w-10 h-10 rounded-full"> -->
              <div>
                <div class="font-medium">Michael Thompson</div>
                <div class="text-gray-500">Commercial Fisherman, British Columbia</div>
              </div>
            </div>
          </footer>
        </blockquote>
      </div>
    </div>
  </div>
</section>

<section class="bg-gradient-to-r from-green-500 to-yellow-500 text-white py-12 md:py-20">
  <div class="container mx-auto px-4 md:px-8">
    <h2 class="text-3xl md:text-4xl font-bold mb-8">Download Truewind Now</h2>
    <div class="flex justify-center">
      <a href="https://apps.apple.com/no/app/truewind/id6470672268" class="mr-4 hover:text-gray-300">
        <img src="/assets/iosdownload.svg" class="h-20 inline-block mr-2 py-3" />
      </a>
      <a href='https://play.google.com/store/apps/details?id=app.tidebyte.marineweather&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1' class="mr-4 hover:text-gray-300">
        <img alt='Get it on Google Play' src='/assets/androiddownload.png' class="h-20 inline-block mr-2" />
      </a>
    </div>
  </div>
</section>

<section class="bg-gradient-to-r from-pink-500 to-purple-500 text-white py-12 md:py-20">
  <div class="container mx-auto px-4 md:px-8">
    <h2 class="text-3xl md:text-4xl font-bold mb-8">Latest from the Truewind Blog</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
    {% for post in site.posts %}
      <a href="{{ post.url }}" class="bg-white rounded-lg shadow-lg overflow-hidden text-gray-900">
        <img src="{{post.image}}" alt="Blog Post Image" class="w-full h-48 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-bold mb-2">{{ post.title }}</h3>
          <p class="text-gray-500">{{ post.excerpt }}</p>
        </div>
      </a>
    {% endfor %}
  </div>
  </div>
</section>
