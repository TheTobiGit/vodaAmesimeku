<template>
  <div class="p-4 flex flex-col gap-5 bg-[#fefefe]">
    <div class="w-full border bg-[#f8f8f8] rounded-md p-2 flex flex-col gap-5">
      <Icon name="ion:radio-waves" color="red" size="2rem" />
      <div class="w-full h-3 rounded-md bg-[#d9d9d9]">
        <div class="h-full w-[35%] bg-red-600 rounded-md"></div>
      </div>
      <div class="flex justify-between">
        <div>
          <p class="text-[11px] text-gray-500">Your data</p>
          <p class="font-bold">
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
          <p class="font-bold flex items-center">
            <Icon name="fa6-solid:cedi-sign" /> 4.32
          </p>
        </div>
      </div>
      <div
        class="border rounded-md w-[46%] p-2 flex flex-col gap-8 bg-[#f8f8f8]"
      >
        <Icon name="ci:bookmark" color="red" size="2rem" />
        <div>
          <p class="font-bold">Pay Bill</p>
          <p class="text-[11px] text-gray-500">
            Make payments for your postpaid services
          </p>
        </div>
      </div>
    </div>

    <p class="font-bold">Manage</p>

    <div class="w-full mb-1">
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
          <Icon
            name="ph:device-mobile-camera-light"
            size="2rem"
            class="rotate-180"
          />
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
    </div>
  </div>
</template>
