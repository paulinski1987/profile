<script>
  import ThemeSwitch from "../ThemeSwitch/ThemeSwitch.svelte";
</script>


      <!-- Sidebar -->
      <!-- This sidebar was adapted from the "Tailwind CSS Admin Dashboard along with dark mode & responsive sidebar"  created by Robin Hossain (https://tailwindcomponents.com/u/robin-hossain) -->

      <!-- Personal info and contact section -->
      <div class="fixed flex flex-col  left-0 w-14 hover:w-64 md:w-64 bg-blue-900 dark:bg-gray-900 h-full text-white transition-all duration-300 border-none z-10 sidebar">
        <div class="overflow-y-auto overflow-x-hidden flex flex-col justify-between flex-grow">
          <ul class="flex flex-col py-4 space-y-1">
            <li class="px-5 hidden md:block">
              <div class="flex flex-row items-center h-8">
                <div class="text-sm font-light tracking-wide text-gray-400 uppercase">Main</div>
              </div>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-blue-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-blue-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M22 10.7602V17.5967C22 19.4377 20.5076 20.93 18.6667 20.93H17.4444C16.8922 20.93 16.4444 20.4823 16.4444 19.93V19.7078C16.4444 19.1555 16.8922 18.7078 17.4444 18.7078H18.6667C19.2803 18.7078 19.7778 18.2104 19.7778 17.5967V10.7602C19.7778 10.4141 19.6165 10.0878 19.3416 9.87755L12.6749 4.77951C12.2765 4.47486 11.7235 4.47485 11.3251 4.77951L4.65839 9.87755C4.38348 10.0878 4.22222 10.4141 4.22222 10.7602V17.5967C4.22222 18.2104 4.71968 18.7078 5.33333 18.7078H6.55556C7.10784 18.7078 7.55556 19.1555 7.55556 19.7078V19.93C7.55556 20.4823 7.10784 20.93 6.55556 20.93H5.33333C3.49239 20.93 2 19.4377 2 17.5967V10.7602C2 9.72193 2.48377 8.74299 3.3085 8.11231L9.97517 3.01427C11.1704 2.1003 12.8297 2.10031 14.0248 3.01427L20.6915 8.11231C21.5162 8.74299 22 9.72194 22 10.7602ZM11.8889 11.1523H12.1111C13.768 11.1523 15.1111 12.4954 15.1111 14.1523V17.7078C15.1111 19.3647 13.768 20.7078 12.1111 20.7078H11.8889C10.232 20.7078 8.88889 19.3647 8.88889 17.7078V14.1523C8.88889 12.4954 10.232 11.1523 11.8889 11.1523ZM13.1111 14.1523C13.1111 13.6 12.6634 13.1523 12.1111 13.1523H11.8889C11.3366 13.1523 10.8889 13.6 10.8889 14.1523V17.7078C10.8889 18.2601 11.3366 18.7078 11.8889 18.7078H12.1111C12.6634 18.7078 13.1111 18.2601 13.1111 17.7078V14.1523Z" fill="#000000"/></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Home</span>
              </a>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-blue-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-blue-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M12 6C9.79088 6 8.00002 7.79086 8.00002 10C8.00002 12.2091 9.79088 14 12 14C14.2092 14 16 12.2091 16 10C16 7.79086 14.2092 6 12 6ZM10 10C10 8.89543 10.8954 8 12 8C13.1046 8 14 8.89543 14 10C14 11.1046 13.1046 12 12 12C10.8954 12 10 11.1046 10 10Z" fill="#000000"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M19.3281 18.8044C17.502 20.7701 14.8946 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 14.5636 21.0353 16.9019 19.4492 18.6717C19.4574 18.7043 19.4654 18.7371 19.4732 18.7701L19.3281 18.8044ZM4 12C4 7.58172 7.58172 4 12 4C16.4183 4 20 7.58172 20 12C20 13.7512 19.4373 15.3709 18.483 16.6883C18.4787 16.6833 18.4745 16.6783 18.4702 16.6733C17.9897 16.1093 17.3996 15.7355 16.7537 15.4902C15.5207 15.0218 13.9981 15 12.5 15H11.5C10.0157 15 8.58663 15.0178 7.4546 15.5071C6.72237 15.8235 6.15855 16.3097 5.73753 16.9786C4.6499 15.6123 4 13.8821 4 12ZM7.23094 18.4237C8.56265 19.414 10.2129 20 12 20C13.9364 20 15.7121 19.312 17.096 18.1672C17.048 18.0951 16.9985 18.0298 16.9479 17.9704C16.7202 17.7032 16.4289 17.5062 16.0436 17.3598C15.2144 17.0449 14.0755 17 12.5 17H11.5C9.91075 17 8.9284 17.0489 8.2481 17.3429C7.85089 17.5146 7.50217 17.7968 7.23094 18.4237Z" fill="#000000"/></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">About</span>
              </a>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-blue-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-blue-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.9886 20.9463L12.88 19.9522L12.35 20.0101L12.1027 20.4825L12.9886 20.9463ZM6.45572 19.09L7.06966 19.8793L8.08109 19.0927L7.07226 18.3027L6.45572 19.09ZM4.23006 20.8211L3.61612 20.0317L3.61611 20.0317L4.23006 20.8211ZM20 12C20 16.1206 16.8838 19.5148 12.88 19.9522L13.0973 21.9404C18.1043 21.3933 22 17.1523 22 12H20ZM12 4C16.4183 4 20 7.58172 20 12H22C22 6.47715 17.5228 2 12 2V4ZM4 12C4 7.58172 7.58172 4 12 4V2C6.47715 2 2 6.47715 2 12H4ZM7.07226 18.3027C5.20015 16.8366 4 14.5587 4 12H2C2 15.1996 3.50381 18.0485 5.83917 19.8773L7.07226 18.3027ZM4.844 21.6104L7.06966 19.8793L5.84178 18.3006L3.61612 20.0317L4.844 21.6104ZM4.29145 20C5.1484 20 5.52041 21.0843 4.84401 21.6104L3.61611 20.0317C2.78939 20.6747 3.24408 22 4.29145 22V20ZM12 20H4.29145V22H12V20ZM12.9 20H12V22H12.9V20ZM12.1027 20.4825C12.2517 20.1979 12.5519 20 12.9 20V22C13.3252 22 13.6921 21.7586 13.8746 21.4102L12.1027 20.4825Z" fill="#000000"/>
                    <path d="M9 12C9 12.5523 8.55228 13 8 13C7.44772 13 7 12.5523 7 12C7 11.4477 7.44772 11 8 11C8.55228 11 9 11.4477 9 12Z" fill="#000000"/>
                    <path d="M13 12C13 12.5523 12.5523 13 12 13C11.4477 13 11 12.5523 11 12C11 11.4477 11.4477 11 12 11C12.5523 11 13 11.4477 13 12Z" fill="#000000"/>
                    <path d="M17 12C17 12.5523 16.5523 13 16 13C15.4477 13 15 12.5523 15 12C15 11.4477 15.4477 11 16 11C16.5523 11 17 11.4477 17 12Z" fill="#000000"/></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Contact</span>
              </a>
            </li>

            <!-- Portfolio section -->

            <li class="px-5 hidden md:block">
              <div class="flex flex-row items-center mt-5 h-8">
                <div class="text-sm font-light tracking-wide text-gray-400 uppercase">Portfolio</div>
              </div>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-blue-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-blue-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M2 6C2 4.34315 3.34315 3 5 3H19C20.6569 3 22 4.34315 22 6V15C22 16.6569 20.6569 18 19 18H13V19H15C15.5523 19 16 19.4477 16 20C16 20.5523 15.5523 21 15 21H9C8.44772 21 8 20.5523 8 20C8 19.4477 8.44772 19 9 19H11V18H5C3.34315 18 2 16.6569 2 15V6ZM5 5C4.44772 5 4 5.44772 4 6V15C4 15.5523 4.44772 16 5 16H19C19.5523 16 20 15.5523 20 15V6C20 5.44772 19.5523 5 19 5H5Z" fill="#000000"/></svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Desktop</span>
              </a>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-blue-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-blue-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M8 2C6.34315 2 5 3.34315 5 5V19C5 20.6569 6.34315 22 8 22H16C17.6569 22 19 20.6569 19 19V5C19 3.34315 17.6569 2 16 2H8ZM7 5C7 4.44772 7.44772 4 8 4H16C16.5523 4 17 4.44772 17 5V19C17 19.5523 16.5523 20 16 20H8C7.44772 20 7 19.5523 7 19V5ZM10 17C9.44772 17 9 17.4477 9 18C9 18.5523 9.44772 19 10 19H14C14.5523 19 15 18.5523 15 18C15 17.4477 14.5523 17 14 17H10Z" fill="#000000"/>
                  </svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Mobile</span>
              </a>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-blue-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-blue-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M17.8321 9.5547C18.1384 9.09517 18.0142 8.4743 17.5547 8.16795C17.0952 7.8616 16.4743 7.98577 16.168 8.4453L13.3925 12.6085L10.0529 10.3542C9.421 9.92768 8.55941 10.1339 8.18917 10.8004L6.12584 14.5144C5.85763 14.9971 6.03157 15.6059 6.51436 15.8742C6.99714 16.1424 7.60594 15.9684 7.87416 15.4856L9.56672 12.439L12.8571 14.66C13.4546 15.0634 14.2662 14.9035 14.6661 14.3036L17.8321 9.5547Z" fill="#000000"/>
<path fill-rule="evenodd" clip-rule="evenodd" d="M7 2C4.23858 2 2 4.23858 2 7V17C2 19.7614 4.23858 22 7 22H17C19.7614 22 22 19.7614 22 17V7C22 4.23858 19.7614 2 17 2H7ZM4 7C4 5.34315 5.34315 4 7 4H17C18.6569 4 20 5.34315 20 7V17C20 18.6569 18.6569 20 17 20H7C5.34315 20 4 18.6569 4 17V7Z" fill="#000000"/>
                  </svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Data Visualization</span>
              </a>
            </li>
            <li>
              <a href="#" class="relative flex flex-row items-center h-11 focus:outline-none hover:bg-blue-800 dark:hover:bg-gray-600 text-white-600 hover:text-white-800 border-l-4 border-transparent hover:border-blue-500 dark:hover:border-gray-800 pr-6">
                <span class="inline-flex justify-center items-center ml-4">
                  <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M16.0563 9.08667C16.5075 8.7626 17.1448 8.86318 17.389 9.36214C17.7211 10.0405 17.9234 10.7783 17.9821 11.5373C18.0668 12.6322 17.8494 13.7293 17.3536 14.7091C16.8577 15.6889 16.1025 16.5139 15.1702 17.0941C14.2379 17.6743 13.1642 17.9875 12.0661 17.9996C10.968 18.0117 9.8877 17.7222 8.94281 17.1627C7.99791 16.6032 7.2247 15.7951 6.70741 14.8264C6.19012 13.8577 5.94858 12.7657 6.00913 11.6692C6.0511 10.9091 6.23713 10.167 6.55416 9.4815C6.78734 8.97728 7.42223 8.86269 7.88047 9.17673C8.33871 9.49078 8.44139 10.1155 8.25163 10.6377C8.11874 11.0033 8.03945 11.3881 8.0178 11.7801C7.97756 12.509 8.1381 13.2349 8.48196 13.8787C8.82581 14.5226 9.33977 15.0598 9.96785 15.4317C10.5959 15.8036 11.314 15.9961 12.0439 15.988C12.7738 15.98 13.4875 15.7718 14.1073 15.3861C14.727 15.0004 15.229 14.4521 15.5586 13.8008C15.8882 13.1495 16.0327 12.4202 15.9764 11.6924C15.9461 11.301 15.8584 10.918 15.7174 10.5554C15.5162 10.0376 15.6051 9.41073 16.0563 9.08667Z" />
<path d="M12 8V12M21 12C21 16.9706 16.9706 21 12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12Z"  stroke-width="2" stroke-linecap="round"/>
                  </svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Websites</span>
              </a>
            </li>
          </ul>
          <!-- <div class="themeSwitcher absolute bottom-5 right-5">
            <ThemeSwitch />
          </div> -->
        </div>
      </div>
      <div class="themeSwitcher absolute bottom-5 left-5 z-50">
        <ThemeSwitch />
      </div>