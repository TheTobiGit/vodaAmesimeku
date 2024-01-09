<template>
  <Header />
  <div v-if="layoutType" class="p-4 flex flex-col gap-5 bg-gray-50">
    <div class="w-full border bg-[#f8f8f8] rounded-md p-2 flex flex-col gap-5">
      <Icon name="ion:radio-waves" color="red" size="2rem" />
      <div class="w-full h-3 rounded-md bg-[#d9d9d9]">
        <div class="h-full w-[35%] bg-red-600 rounded-md"></div>
      </div>
      <div class="flex justify-between">
        <div>
          <p class="text-[11px] text-gray-500">Your data</p>
          <p class="font-semibold">
            20.45 <span class="text-[10px]">GB left</span>
          </p>
        </div>
        <div class="self-end">
          <p class="text-[11px] text-gray-500">
            of <span class="text-base">300</span> GB
          </p>
        </div>
      </div>
    </div>

    <div class="w-full flex justify-between mb-3">
      <div
        class="border rounded-md w-[45.5%] p-2 flex flex-col gap-10 bg-[#f8f8f8]"
      >
        <Icon
          name="solar:sim-card-minimalistic-broken"
          color="red"
          size="2rem"
        />
        <div>
          <p class="text-[11px] text-gray-500">Your airtime balance</p>
          <p class="font-semibold flex items-center">
            <Icon name="fa6-solid:cedi-sign" /> 4.32
          </p>
        </div>
      </div>
      <div
        class="border rounded-md w-[46%] p-2 flex flex-col gap-8 bg-[#f8f8f8]"
      >
        <Icon name="ci:bookmark" color="red" size="2rem" />
        <div>
          <p class="font-semibold">Pay Bill</p>
          <p class="text-[11px] text-gray-500">
            Make payments for your postpaid services
          </p>
        </div>
      </div>
    </div>

    <p class="font-semibold">Manage</p>

    <div class="w-full flex flex-col gap-[2px]">
      <div class="p-2 flex gap-5 bg-[#ffffff]">
        <div class="bg-[#f8f8f8] w-fit p-2 rounded-full">
          <Icon
            name="material-symbols-light:add-circle-outline-rounded"
            size="2rem"
          />
        </div>
        <div class="flex flex-col">
          <p class="font-semibold">Top up airtime or data</p>
          <p class="text-[11px] text-gray-500">
            Recharge airtime or data using this phone
          </p>
        </div>
        <div class="ml-auto">
          <Icon name="ph:caret-right-light" size="2rem" />
        </div>
      </div>

      <div class="p-2 flex gap-5 bg-[#ffffff]">
        <div class="bg-[#f8f8f8] w-fit p-2 rounded-full">
          <Icon
            name="ph:device-mobile-camera-light"
            size="2rem"
            class="rotate-180"
          />
        </div>
        <div class="flex flex-col">
          <p class="font-semibold">My Subscriptions</p>
          <p class="text-[11px] text-gray-500">Manage all subscriptions</p>
        </div>
        <div class="ml-auto">
          <Icon name="ph:caret-right-light" size="2rem" />
        </div>
      </div>

      <div class="p-2 flex gap-5 bg-[#ffffff]">
        <div class="bg-[#f8f8f8] w-fit p-2 rounded-full">
          <Icon name="bi:stars" size="2rem" class="rotate-180" />
        </div>
        <div class="flex flex-col">
          <p class="font-semibold">Value-Added Services</p>
          <p class="text-[11px] text-gray-500">Manage all subscriptions</p>
        </div>
        <div class="ml-auto">
          <Icon name="ph:caret-right-light" size="2rem" />
        </div>
      </div>

      <div class="p-2 flex gap-5 bg-[#ffffff]">
        <div class="bg-[#f8f8f8] w-fit p-2 rounded-full">
          <Icon name="ph:gift" size="2rem" />
        </div>
        <div class="flex flex-col">
          <p class="font-semibold">Red Loyalty Rewards</p>
          <p class="text-[11px] text-gray-500">Get your bag</p>
        </div>
        <div class="ml-auto">
          <Icon name="ph:caret-right-light" size="2rem" />
        </div>
      </div>
    </div>
  </div>

  <div v-else class="p-4 flex flex-col gap-5">
    <div class="w-full flex justify-between mb-3 flex-wrap gap-4">
      <div
        class="border rounded-md w-[46%] p-2 flex flex-col gap-10 bg-[#f8f8f8]"
      >
        <Icon name="ion:radio-waves" color="red" size="2rem" />
        <div>
          <p class="text-[11px] text-gray-500">Your data</p>
          <p class="font-semibold">
            20.45 <span class="text-[10px]">GB </span>
          </p>
        </div>
      </div>

      <div
        class="border rounded-md w-[46%] p-2 flex flex-col gap-10 bg-[#f8f8f8]"
      >
        <Icon
          name="solar:sim-card-minimalistic-broken"
          color="red"
          size="2rem"
        />
        <div>
          <p class="text-[11px] text-gray-500">Your airtime balance</p>
          <p class="font-semibold flex items-center">
            <Icon name="fa6-solid:cedi-sign" /> 4.32
          </p>
        </div>
      </div>

      <div
        class="border rounded-md w-[46%] p-2 flex flex-col gap-8 bg-[#f8f8f8]"
      >
        <Icon name="ci:bookmark" color="red" size="2rem" />
        <div>
          <p class="font-semibold">Pay Bill</p>
          <p class="text-[11px] text-gray-500">
            Make payments for your postpaid services
          </p>
        </div>
      </div>
    </div>

    <p class="font-semibold">Manage</p>

    <div class="w-full flex justify-between mb-3 flex-wrap gap-4">
      <div
        class="border rounded-md w-[46%] p-2 flex flex-col gap-10 bg-[#f8f8f8]"
      >
        <Icon name="ph:device-mobile-camera-light" size="2rem" />
        <p>Top Up Airtime Or Data</p>
      </div>

      <div
        class="border rounded-md w-[46%] p-2 flex flex-col gap-10 bg-[#f8f8f8]"
      >
        <Icon name="ion:radio-waves" size="2rem" />
        <p>My Subscriptions</p>
      </div>

      <div
        class="border rounded-md w-[46%] p-2 flex flex-col gap-10 bg-[#f8f8f8]"
      >
        <Icon name="bi:stars" size="2rem" />
        <p>Value-Added Services</p>
      </div>

      <div
        class="border rounded-md w-[46%] p-2 flex flex-col gap-10 bg-[#f8f8f8]"
      >
        <Icon name="ph:gift" size="2rem" />
        <p>Red Loyalty Rewards</p>
      </div>
    </div>
  </div>

  <Footer @layout-toggle="handleLayoutToggle" />
</template>

<script setup>
const layoutType = ref(true);

function handleLayoutToggle() {
  layoutType.value = !layoutType.value;
}
</script>
