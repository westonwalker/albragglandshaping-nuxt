<template>

  <div class="mb-12 w-full md:w-1/2 lg:w-1/4 px-4">
    <img :src="image" alt="" class=" mb-6 w-full h-64 object-cover rounded-lg">
    <h4 class="mb-4 text-2xl font-bold font-heading">
      {{title}}
    </h4>
    <p class="text-gray-500 leading-loose">
      {{description}}
    </p>
  </div>
</template>

<script>
export default {
  props: ["title", "description", "image"],
};
</script>
