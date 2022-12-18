<template>
  <header>
    <div class="header-wrapper p-4">
      <div class="brand-name pb-4 header">
        <button class="sidebar-menu">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="28px"
            viewBox="0 0 24 24"
            width="28px"
            fill="#fff"
          >
            <path d="M0 0h24v24H0z" fill="none" />
            <path
              d="M3 13h2v-2H3v2zm0 4h2v-2H3v2zm0-8h2V7H3v2zm4 4h14v-2H7v2zm0 4h14v-2H7v2zM7 7v2h14V7H7z"
            />
          </svg>
        </button>
        <h1 class="mx-auto">SuperCook</h1>
      </div>
      <div class="search-bar">
        <b-form-input
          v-model="searchValue"
          class="pl-5"
          type="search"
          placeholder="Find..."
        >
        </b-form-input>
        <span class="mdi mdi-magnify"></span>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      searchValue: null,
    }
  },

  mounted() {},

  methods: {},
}
</script>

<style lang="scss" scoped></style>
