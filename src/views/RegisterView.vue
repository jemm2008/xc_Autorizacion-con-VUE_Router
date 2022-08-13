<template>
    <section class="register">
        <v-container fill-height>
            <v-row justify="center">
                <v-col cols="3">
                    <register-form></register-form>
                </v-col>
            </v-row>
        </v-container>
    </section>
</template>

<script>
import RegisterForm from '@/components/RegisterForm.vue'

export default {
    name: 'register-view',
    data: function(){
        return {}
    },
    components: {
        'register-form': RegisterForm
    },
}
</script>

<style scoped lang="scss">
section {
    height: 100vh;
}
</style>