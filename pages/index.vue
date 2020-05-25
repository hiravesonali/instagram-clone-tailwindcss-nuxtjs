<template>
  <div>
    <nav class="bg-white shadow px-48 border-b border-gray-400">
      <div class="max-w-7xl mx-auto px-2 sm:px-4 lg:px-8">
        <div class="flex justify-between h-16">
          <div class="flex px-2 lg:px-0">
            <div class="flex-shrink-0 flex items-center">
              <img
                class="block lg:hidden h-8 w-auto"
                src="https://www.instagram.com/static/images/web/mobile_nav_type_logo.png/735145cfe0a4.png"
                alt="Workflow logo"
              />
              <img
                class="hidden lg:block h-8 w-auto"
                src="https://www.instagram.com/static/images/web/mobile_nav_type_logo.png/735145cfe0a4.png"
                alt="Workflow logo"
              />
            </div>
          </div>
          <div class="flex-1 flex items-center justify-center px-2 lg:ml-12">
            <div class="max-w-lg w-full lg:max-w-xs">
              <label for="search" class="sr-only">Search</label>
              <div class="relative">
                <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                  <svg class="h-5 w-5 text-gray-500" fill="currentColor" viewBox="0 0 20 20">
                    <path
                      fill-rule="evenodd"
                      d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </div>
                <input
                  id="search"
                  class="block w-full pl-10 pr-3 py-2 border border-gray-400 rounded-md leading-5 bg-gray-100 placeholder-gray-500 focus:outline-none focus:placeholder-gray-400 focus:border-blue-300 focus:shadow-outline-blue sm:text-sm transition duration-150 ease-in-out"
                  placeholder="Search"
                  type="search"
                />
              </div>
            </div>
          </div>
          <div class="flex items-center lg:hidden">
            <!-- Mobile menu button -->
            <button
              class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:bg-gray-100 focus:text-gray-500 transition duration-150 ease-in-out"
              aria-label="Main menu"
              aria-expanded="false"
            >
              <!-- Icon when menu is closed. -->
              <!-- Menu open: "hidden", Menu closed: "block" -->
              <svg class="block h-6 w-6" stroke="currentColor" fill="none" viewBox="0 0 24 24">
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M4 6h16M4 12h16M4 18h16"
                />
              </svg>
              <!-- Icon when menu is open. -->
              <!-- Menu open: "block", Menu closed: "hidden" -->
              <svg class="hidden h-6 w-6" stroke="currentColor" fill="none" viewBox="0 0 24 24">
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M6 18L18 6M6 6l12 12"
                />
              </svg>
            </button>
          </div>
          <!-- icons-->
          <div class="lg:ml-4 lg:flex lg:items-center">
            <button
              class="flex-shrink-0 p-1 border-transparent text-gray-700 rounded-full hover:text-gray-600 focus:outline-none focus:text-gray-600 transition duration-150 ease-in-out"
              aria-label="Notifications"
            >
              <svg
                class="h-6 w-6"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="1.5"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
                />
              </svg>
            </button>

            <button
              class="flex-shrink-0 p-1 border-transparent text-gray-700 rounded-full hover:text-gray-600 focus:outline-none focus:text-gray-600 transition duration-150 ease-in-out"
              aria-label="Notifications"
            >
              <svg
                class="h-6 w-6"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="1.5"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M16 15v-1a4 4 0 00-4-4H8m0 0l3 3m-3-3l3-3m9 14V5a2 2 0 00-2-2H6a2 2 0 00-2 2v16l4-2 4 2 4-2 4 2z"
                />
              </svg>
            </button>

            <button
              class="flex-shrink-0 p-1 border-transparent text-gray-700 rounded-full hover:text-gray-600 focus:outline-none focus:text-gray-600 transition duration-150 ease-in-out"
              aria-label="Notifications"
            >
              <svg
                class="h-6 w-6"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="1.5"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-5 0a4 4 0 11-8 0 4 4 0 018 0z"
                />
              </svg>
            </button>

            <button
              class="flex-shrink-0 p-1 border-transparent text-gray-700 rounded-full hover:text-gray-600 focus:outline-none focus:text-gray-600 transition duration-150 ease-in-out"
              aria-label="Notifications"
            >
              <svg
                class="h-6 w-6"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="1.5"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"
                />
              </svg>
            </button>

            <!-- Profile dropdown -->
            <div class="ml-4 relative flex-shrink-0">
              <div>
                <button
                  class="flex rounded-full border-gray-700 transition duration-150 ease-in-out"
                  id="user-menu"
                  aria-label="User menu"
                  aria-haspopup="true"
                >
                  <img
                    class="h-8 w-8 rounded-full"
                    src="https://scontent-muc2-1.cdninstagram.com/v/t51.2885-19/s150x150/58468664_291773768419326_7460980271920185344_n.jpg?_nc_ht=scontent-muc2-1.cdninstagram.com&amp;_nc_ohc=16Or2MWYINEAX9vLBW0&amp;oh=ada3818c35cb64180cf431d820d9dabe&amp;oe=5EF26035"
                    alt
                  />
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <!--body start-->
    <!--profile data-->
    <div class="bg-gray-100 h-auto px-48">
      <div class="flex md:flex-row-reverse flex-wrap">
        <div class="w-full md:w-3/4 p-4 text-center">
          <div class="text-left pl-4 pt-3">
            <span class="text-base text-gray-700 text-2xl mr-2">HiraveSonali</span>
            <span class="text-base font-semibold text-gray-700 mr-2">
              <button
                class="bg-transparent hover:bg-blue-500 text-gray-700 font-semibold hover:text-white py-2 px-4 border border-gray-600 hover:border-transparent rounded"
              >Edit Profile</button>
            </span>
            <span class="text-base font-semibold text-gray-700">
              <button
                class="p-1 border-transparent text-gray-700 rounded-full hover:text-blue-600 focus:outline-none focus:text-gray-600"
                aria-label="Notifications"
              >
                <svg
                  class="h-8 w-8"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="1.5"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
                  />
                  <path d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                </svg>
              </button>
            </span>
          </div>

          <div class="text-left pl-4 pt-3">
            <span class="text-base font-semibold text-gray-700 mr-2">
              <b>220</b> posts
            </span>
            <span class="text-base font-semibold text-gray-700 mr-2">
              <b>114</b> followers
            </span>
            <span class="text-base font-semibold text-gray-700">
              <b>200</b> following
            </span>
          </div>

          <div class="text-left pl-4 pt-3">
            <span class="text-lg font-bold text-gray-700 mr-2">Sonali Hirave</span>
          </div>

          <div class="text-left pl-4 pt-3">
            <p
              class="text-base font-medium text-blue-700 mr-2"
            >#graphicsdesigner #traveller #reader #blogger #digitalmarketer</p>
            <p
              class="text-base font-medium text-gray-700 mr-2"
            >https://www.behance.net/hiravesona7855</p>
          </div>
        </div>

        <div class="w-full md:w-1/4 p-4 text-center">
          <div class="w-full relative md:w-3/4 text-center mt-8">
            <button
              class="flex rounded-full"
              id="user-menu"
              aria-label="User menu"
              aria-haspopup="true"
            >
              <img
                class="h-40 w-40 rounded-full"
                src="https://scontent-muc2-1.cdninstagram.com/v/t51.2885-19/s150x150/58468664_291773768419326_7460980271920185344_n.jpg?_nc_ht=scontent-muc2-1.cdninstagram.com&amp;_nc_ohc=16Or2MWYINEAX9vLBW0&amp;oh=ada3818c35cb64180cf431d820d9dabe&amp;oe=5EF26035"
                alt
              />
            </button>
          </div>
        </div>
      </div>

      <!--status show icon-->

      <div class="inline-flex ml-36 mt-16">
        <div class="flex-1 text-center px-4 py-2 m-2">
          <div
            class="relative shadow-xl mx-auto h-24 w-24 -my-12 border-white rounded-full overflow-hidden border-4"
          >
            <img
              class="object-cover w-full h-full"
              src="https://scontent-muc2-1.cdninstagram.com/v/t51.12442-15/e35/c159.407.315.315a/s150x150/91073381_504497763549014_6507821149661558216_n.jpg?_nc_ht=scontent-muc2-1.cdninstagram.com&_nc_cat=102&_nc_ohc=JIhoQ3kD5HMAX-uGdLX&oh=3ad3d9cce1a28659dfb4c823f11dd5f0&oe=5ECB8D58"
            />
          </div>
          <h1 class="pt-16 text-base font-semibold text-gray-900">Fun</h1>
        </div>

        <div class="flex-1 text-center px-4 py-2 m-2">
          <div
            class="relative shadow-xl mx-auto h-24 w-24 -my-12 border-white rounded-full overflow-hidden border-4"
          >
            <img
              class="object-cover w-full h-full"
              src="https://scontent-muc2-1.cdninstagram.com/v/t51.2885-19/s150x150/58468664_291773768419326_7460980271920185344_n.jpg?_nc_ht=scontent-muc2-1.cdninstagram.com&amp;_nc_ohc=16Or2MWYINEAX9vLBW0&amp;oh=ada3818c35cb64180cf431d820d9dabe&amp;oe=5EF26035"
            />
          </div>
          <h1 class="pt-16 text-base font-semibold text-gray-900">Travel</h1>
        </div>

        <div class="flex-1 text-center px-4 py-2 m-2">
          <div
            class="relative shadow-xl mx-auto h-24 w-24 -my-12 border-white rounded-full overflow-hidden border-4"
          >
            <img
              class="object-cover w-full h-full"
              src="https://scontent-muc2-1.cdninstagram.com/v/t51.12442-15/e35/c0.403.928.928a/s150x150/61196089_2347348488871080_6555463159074971094_n.jpg?_nc_ht=scontent-muc2-1.cdninstagram.com&_nc_cat=100&_nc_ohc=vNccrTA01CwAX8dO3YS&oh=9b67a83895bdc5ca62f53a0f43cd8131&oe=5ECB760C"
            />
          </div>
          <h1 class="pt-16 text-base font-semibold text-gray-900">Food</h1>
        </div>

        <div class="flex-1 text-center px-4 py-2 m-2">
          <div
            class="relative shadow-xl mx-auto h-24 w-24 -my-12 border-white rounded-full overflow-hidden border-4"
          >
            <img
              class="object-cover w-full h-full"
              src="https://scontent-muc2-1.cdninstagram.com/v/t51.12442-15/e35/c159.407.315.315a/s150x150/91073381_504497763549014_6507821149661558216_n.jpg?_nc_ht=scontent-muc2-1.cdninstagram.com&_nc_cat=102&_nc_ohc=JIhoQ3kD5HMAX-uGdLX&oh=3ad3d9cce1a28659dfb4c823f11dd5f0&oe=5ECB8D58"
            />
          </div>
          <h1 class="pt-16 text-base font-semibold text-gray-900">Sketch</h1>
        </div>

        <div class="flex-1 text-center px-4 py-2 m-2">
          <div
            class="relative shadow-xl mx-auto h-24 w-24 -my-12 border-white rounded-full overflow-hidden border-4"
          >
            <img
              class="object-cover w-full h-full"
              src="https://scontent-muc2-1.cdninstagram.com/v/t51.12442-15/e35/c159.407.315.315a/s150x150/91073381_504497763549014_6507821149661558216_n.jpg?_nc_ht=scontent-muc2-1.cdninstagram.com&_nc_cat=102&_nc_ohc=JIhoQ3kD5HMAX-uGdLX&oh=3ad3d9cce1a28659dfb4c823f11dd5f0&oe=5ECB8D58"
            />
          </div>
          <h1 class="pt-16 text-base font-semibold text-gray-900">My Work</h1>
        </div>
      </div>

      <hr class="border-gray-500 mt-6" />
      <hr class="border-gray-500 w-20 border-t-1 ml-64 border-gray-800" />

      <!--post icon and title-->
      <div class="flex flex-row mt-4 justify-center mr-16">
        <div class="flex text-gray-700 text-center py-2 m-2 pr-5">
          <div class="flex inline-flex">
            <button
              class="border-transparent text-gray-800 rounded-full hover:text-blue-600 focus:outline-none focus:text-gray-600"
              aria-label="Notifications"
            >
              <svg
                class="h-6 w-6"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M17 14v6m-3-3h6M6 10h2a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v2a2 2 0 002 2zm10 0h2a2 2 0 002-2V6a2 2 0 00-2-2h-2a2 2 0 00-2 2v2a2 2 0 002 2zM6 20h2a2 2 0 002-2v-2a2 2 0 00-2-2H6a2 2 0 00-2 2v2a2 2 0 002 2z"
                />
              </svg>
            </button>
          </div>
          <div class="flex inline-flex ml-2 mt-1">
            <h3 class="text-sm font-bold text-gray-800 mr-2">POSTS</h3>
          </div>
        </div>

        <div class="flex text-gray-700 text-center py-2 m-2 pr-5">
          <div class="flex inline-flex">
            <button
              class="border-transparent text-gray-600 rounded-full hover:text-blue-600 focus:outline-none focus:text-gray-600"
              aria-label="Notifications"
            >
              <svg
                class="h-6 w-6"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                />
              </svg>
            </button>
          </div>
          <div class="flex inline-flex ml-2 mt-1">
            <h3 class="text-sm font-medium text-gray-700 mr-2">IGTV</h3>
          </div>
        </div>

        <div class="flex text-gray-700 text-center py-2 m-2 pr-5">
          <div class="flex inline-flex">
            <button
              class="border-transparent text-gray-600 rounded-full hover:text-blue-600 focus:outline-none focus:text-gray-600"
              aria-label="Notifications"
            >
              <svg
                class="h-6 w-6"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z" />
              </svg>
            </button>
          </div>
          <div class="flex inline-flex ml-2 mt-1">
            <h3 class="text-sm font-medium text-gray-700 mr-2">SAVED</h3>
          </div>
        </div>

        <div class="flex text-gray-700 text-center py-2 m-2 pr-5">
          <div class="flex inline-flex">
            <button
              class="border-transparent text-gray-600 rounded-full hover:text-blue-600 focus:outline-none focus:text-gray-600"
              aria-label="Notifications"
            >
              <svg
                class="h-6 w-6"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M18 9v3m0 0v3m0-3h3m-3 0h-3m-2-5a4 4 0 11-8 0 4 4 0 018 0zM3 20a6 6 0 0112 0v1H3v-1z"
                />
              </svg>
            </button>
          </div>
          <div class="flex inline-flex ml-2 mt-1">
            <h3 class="text-sm font-medium text-gray-700 mr-2">TAGGED</h3>
          </div>
        </div>
      </div>

      <!--post images-->

      <div class="flex pt-4">
        <div class="flex-1 text-center px-4 py-2 m-2">
          <img
            class="w-full"
            src="https://images.unsplash.com/photo-1487530811176-3780de880c2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
          />
        </div>
        <div class="flex-1 text-center px-4 py-2 m-2">
          <img
            class="w-full"
            src="https://images.unsplash.com/photo-1487530811176-3780de880c2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
          />
        </div>
        <div class="flex-1 text-center px-4 py-2 m-2">
          <img
            class="w-full"
            src="https://images.unsplash.com/photo-1487530811176-3780de880c2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
          />
        </div>
      </div>

      <div class="flex pt-4">
        <div class="flex-1 text-center px-4 py-2 m-2">
          <img
            class="w-full"
            src="https://images.unsplash.com/photo-1487530811176-3780de880c2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
          />
        </div>
        <div class="flex-1 text-center px-4 py-2 m-2">
          <img
            class="w-full"
            src="https://images.unsplash.com/photo-1487530811176-3780de880c2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
          />
        </div>
        <div class="flex-1 text-center px-4 py-2 m-2">
          <img
            class="w-full"
            src="https://images.unsplash.com/photo-1487530811176-3780de880c2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
          />
        </div>
      </div>

      <div class="flex pt-4">
        <div class="flex-1 text-center px-4 py-2 m-2">
          <img
            class="w-full"
            src="https://images.unsplash.com/photo-1487530811176-3780de880c2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
          />
        </div>
        <div class="flex-1 text-center px-4 py-2 m-2">
          <img
            class="w-full"
            src="https://images.unsplash.com/photo-1487530811176-3780de880c2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
          />
        </div>
        <div class="flex-1 text-center px-4 py-2 m-2">
          <img
            class="w-full"
            src="https://images.unsplash.com/photo-1487530811176-3780de880c2d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {}
};
</script>
