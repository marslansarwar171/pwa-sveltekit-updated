<script>
  import { openModal } from "../store";
</script>

<header class="flex flex-col relative z-20 bg-green-500">
  <div
    class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6"
  >
    <a href="/">
      <h1 class="font-semibold">
        Web <span class="text-indigo-400">Academy</span>
      </h1>
    </a>
    <button
      on:click={() => ($openModal = true)}
      class="md:hidden grid place-items-center"
    >
      <i class="fa-solid fa-bars"></i>
    </button>
    <nav class="hidden md:flex items-center gap-4 lg:gap-6">
      <a
        href="#conversion"
        class="duration-200 hover:text-indigo-400 cursor-pointer">Conversion</a
      >
      <button class="specialBtn">
        <p>Signup Now</p>
      </button>
    </nav>
  </div>
</header>