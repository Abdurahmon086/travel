<template>
  <header class="fixed backdrop-blur-sm bg-[#00000063] top-0 left-0 z-50 w-full">
    <div
      class="container mx-auto h-16 flex items-center justify-between border-b-[1px] border-white"
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
  <footer><h4>FOOTER</h4></footer>
</template>

