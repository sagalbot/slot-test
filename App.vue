<template>
  <div>
    <h1>
      Hello <name #default="{person}">{{ person }}</name>
    </h1>
  </div>
</template>

<script>
import Name from './Name'
export default {
  components: {Name},
}
</script>
