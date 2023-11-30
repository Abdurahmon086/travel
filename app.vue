<template>
  <header
    class="fixed backdrop-blur-sm bg-[#00000063] top-0 left-0 z-50 w-full"
  >
    <div
      class="container1 mx-auto h-16 flex items-center justify-between border-b-[1px] border-white"
    >
      <a href="/" class="flex items-center gap-3">
        <img
          class="w-5 h-6"
          src="https://static.tildacdn.com/tild3464-3432-4365-b439-383037373638/logo_goodwill.svg"
          alt="logo icon"
        />
        <h4 class="text-[14px]">Goodwill Realty</h4>
      </a>
      <nav>
        <ul class="flex items-center gap-10">
          <li><a href="#about" class="text-[14px]"> О компании </a></li>
          <li><a href="#catalogue" class="text-[14px]"> Проекты </a></li>
          <li>
            <a href="#features" class="text-[14px]"> Преимущества покупки </a>
          </li>
          <li><a href="#contact" class="text-[14px]"> Контакты </a></li>
        </ul>
      </nav>
      <a href="tel:" class="text-[14px] mr-24">+ 971 5 886 95492</a>
    </div>
  </header>
  <main>
    <NuxtPage />
  </main>
  <footer>
    <div class="bg-[#403f3f]">
      <div class=" container1 mx-auto px-5">
        <div class="flex justify-between mb-20 pt-16">
          <div class="flex gap-3">
            <a href="#">
              <img
                class="w-11 h-14"
                src="./public/logo_goodwill.svg"
                alt="footer logo"
              />
            </a>
            <div>
              <h4 class="text-white text-2xl">Goodwill Realty</h4>
              <p class="text-[#f9f9f9] text-[10px] font-sans font-normal">
                Агенство недвижимости Дубай
              </p>
            </div>
          </div>

          <div class="flex gap-x-48">
            <div class="flex flex-col">
              <a
                href="#"
                class="text-[#B0B0B0] text-lg font-normal font-sans my-3"
              >
                <span class="mx-3">T:</span>+971 5 886 95492
              </a>

              <a
                href="#"
                class="text-[#B0B0B0] text-lg font-normal font-sans my-3"
              >
                <span class="mx-3">E:</span> dubai@goodwillestate.ae
              </a>
              <div class="flex justify-center">
                <span
                  class="mx-3 my-3 text-[#B0B0B0] text-lg font-normal font-sans"
                  >А:</span
                >
                <a
                  href="#"
                  class="text-[#B0B0B0] text-lg font-normal font-sans my-3"
                >
                  Arenco tower 1806, Dubai <br />
                  Internet City, Dubai, UAE
                </a>
              </div>
            </div>

            <div class="flex flex-col">
              <a
                class="text-[#B0B0B0] text-lg font-normal font-sans mb-2 mt-1 hover:text-white"
                href="#"
                >О компании
              </a>
              <a
                class="text-[#B0B0B0] text-lg font-normal font-sans my-2 hover:text-white"
                href="#"
              >
                Проекты</a
              >
              <a
                class="text-[#B0B0B0] text-lg font-normal font-sans my-2 hover:text-white"
                href="#"
                >Преимущества покупки</a
              >
              <a
                class="text-[#B0B0B0] text-lg font-normal font-sans hover:text-white"
                href="#"
                >Контакты</a
              >
            </div>
          </div>
        </div>
        <div class="flex justify-between gap-x-10 items-center pb-10">
          <p class="text-[#b0b0b0] text-base font-normal font-sans">
            (с) Goodwill Realty 2022
          </p>
          <div class="flex justify-between gap-x-44">
            <a
              href="#"
              class="text-base text-[#b0b0b0] font-sans font-normal hover:text-[#f9f9f9]"
            >
              Разработано Lagom.Design
            </a>
            <a
              href="#"
              class="text-base text-[#b0b0b0] font-sans font-normal hover:text-[#f9f9f9]"
            >
              Политика конфиденциальности
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
