<template>
  <span>
    <slot :person="person">{{ log() }}</slot>
  </span>
</template>

<script>
export default {
  data: () => ({
    person: 'jeff',
  }),
  methods: {
    /* eslint-disable */
    log: () => console.trace(),
  },
};
</script>
