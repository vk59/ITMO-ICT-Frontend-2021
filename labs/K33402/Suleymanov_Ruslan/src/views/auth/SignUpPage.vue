<template>
    <base-auth-layout>
        <sign-up-form />
    </base-auth-layout>
</template>

<script>
    import SignUpForm from '@/components/auth/SignUpForm.vue'
    import BaseAuthLayout from '@/layouts/BaseAuthLayout.vue'

    export default {
        name: "SignUpPage",
        components: { SignUpForm, BaseAuthLayout }
    }
</script>

<style scoped>

</style>