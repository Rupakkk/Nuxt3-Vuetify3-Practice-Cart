<template>
    <v-app-bar>
        <v-toolbar-title @click="$router.push('/')">
            Shopping Website
        </v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn @click="$router.push('/Cart')" class="text-none" stacked>
            <v-badge :content="9" color="error">
                <v-icon>
                    mdi-card-outline
                </v-icon>
            </v-badge>
        </v-btn>
        <v-btn 
            prepend-icon="mdi-weather-sunny"
        >
            Toggle theme
        </v-btn>
    </v-app-bar>>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>