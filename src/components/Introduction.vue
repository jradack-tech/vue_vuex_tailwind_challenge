<template>
  <div class="bg-fixed bg-top bg-cover w-screen h-screen" style="background-image: url('/img/background.png');">

    <div class="flex flex-col w-full items-center p-20 h-full relative overflow-auto ">
      <div class="flex flex-row justify-end py-5 px-10 fixed top-0 w-1/2 h-16 z-10 ">
        <div class="rounded-full w-10 h-10 flex justify-center items-center bg-white">
          i
        </div>
      </div>

      <div class="flex flex-col items-center">
        <div>
          <img src="/img/avatar.png" class="rounded-full w-32 h-32" />
        </div>
        <div class="text-gray-300 p-2 ">Ninja</div>
        <div class="text-gray-300 pb-4  "> I love video games</div>
      </div>

      <div class=" w-1/2 flex flex-col gap-y-5 relative">
        <div class="rounded-2xl  bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>

        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>

        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>

        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>

        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>

        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>
        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>

        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>
        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>
        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>
        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>
        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>
        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>

        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>
        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>
        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>
        <div class="rounded-2xl bg-white shadow flex flex-col justify-center py-5 relative">
          <div class="flex justify-center items-center">Hello</div>
          <div class="bg-red-500 w-5 h-5 absolute ml-5"></div>
        </div>

      </div>
    </div>

  </div>
</template>

<script>
import { createNamespacedHelpers } from "vuex";
const { mapState, mapActions } = createNamespacedHelpers("counter");

export default {
  computed: {
    ...mapState(["count"])
  },
  methods: {
    ...mapActions(["increment", "decrement"])
  }
};
</script>

<style>
.block-text {
  @apply bg-gray-300 inline-block px-2 font-light rounded my-1;
}
</style>