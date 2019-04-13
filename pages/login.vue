<template>
  <div>
    <div v-if="$auth.$state.redirect">
      Redirected from
      <strong>{{ $auth.$state.redirect }}</strong>
    </div>
    <div v-else>
      No redirect.
    </div>
  </div>
</template>

<script>
export default {}
</script>
