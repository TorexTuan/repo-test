<template>
    <form action="">
        <InputField title="Email" placeholder="Enter your email"/>
        <InputField title="Password" placeholder="Enter your password"/>
    </form>
</template>

<script lang="ts">
import InputField from '../components/InputField.vue'

export default ({
  components: {
    InputField
  }
})
</script>
