<template>
  <div class="sticky bottom-0 w-full bg-[#f8f8f8] h-[10vh] px-4">
    <div class="flex justify-evenly items-center h-full w-full">
      <NuxtLink to="/"
        ><div class="flex flex-col items-center">
          <Icon
            name="material-symbols-light:devices-outline-rounded"
            size="2rem"
          />
          <p class="text-[10px]">Services</p>
        </div></NuxtLink
      >

      <NuxtLink to="/Cash">
        <div class="flex flex-col items-center">
          <Icon
            name="material-symbols-light:money-outline-rounded"
            size="2rem"
          />
          <p class="text-[10px]">Cash</p>
        </div></NuxtLink
      >

      <button @click="toggleLayout">
        <img src="../assets/tobi.png" alt="" class="h-[4rem] -translate-y-5" />
      </button>

      <NuxtLink to="/Bundles"
        ><div class="flex flex-col items-center">
          <Icon
            name="material-symbols-light:add-circle-outline-rounded"
            size="2rem"
          />
          <p class="text-[10px]">Bundles</p>
        </div></NuxtLink
      >

      <NuxtLink to="/Settings"
        ><div class="flex flex-col items-center">
          <Icon
            name="material-symbols-light:settings-outline-rounded"
            size="2rem"
          />
          <p class="text-[10px]">Settings</p>
        </div></NuxtLink
      >
    </div>
  </div>
</template>

<script setup>
const emits = defineEmits(["layout-toggle"]);

function toggleLayout() {
  emits("layout-toggle");
}
</script>
