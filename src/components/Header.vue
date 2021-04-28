<template>
  <header class="text-center bg-blue-800 text-white p-4 mb-10">
    <div class="text-3xl md:text-5xl font-bold mb-3">
      <i class="fa fa-viruses"></i> Covid-19 Tracker
    </div>
    <p>
      API by
      <a class="text-blue-300" href="https://covid19api.com" target="_blank"
        >https://covid19api.com</a
      >
    </p>
    <a href="https://github.com/epsooraj/covid-tracker" target="_blank">
      <i class="fab fa-github text-3xl md:text-5xl font-bold mt-3"></i>
    </a>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>
