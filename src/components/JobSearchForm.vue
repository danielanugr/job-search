<template>
  <form
    action=""
    class="flex items-center w-fulls h-12 mt-14 border border-solid border-brand-gray-3 rounded-3xl"
  >
    <FontAwesomeIcon :icon="['fas', 'search']" class="ml-4 mr-3" />
    <div class="flex flex-nowrap flex-1 h-full text-base font-light">
      <div class="relative flex items-center flex-1 h-full pr-3">
        <label for="" class="absolute left-0 -top-10">Role</label>
        <input
          type="text"
          placeholder="Software engineer"
          class="w-full text-lg font-normal focus:outline-none"
        />
      </div>
      <span
        class="flex items-center h-full px-3 border-l border-r border-brand-gray-3 bg-brand-gray-2"
      >
        in
      </span>
      <div class="relative flex items-center flex-1 h-full pl-3">
        <label for="" class="absolute left-0 -top-10">Where?</label>
        <input
          type="text"
          placeholder="Jakarta"
          class="w-full text-lg font-normal focus:outline-none"
        />
      </div>
    </div>

    <ActionButton text="Search" type="secondary" class="rounded-r-3xl" />
  </form>
</template>

<script>
import ActionButton from "@/components/ActionButton.vue";

export default {
  name: "JobSearchForm",
  components: {
    ActionButton,
  },
};
</script>
