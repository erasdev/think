<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Welcome from '@/Components/Welcome.vue';
</script>

<template>
    <AppLayout title="Dashboard" class="bg-blue-100">
        <div class="flex flex-row h-full">
            <div class="absolute w-[12rem] overflow-y-scroll no-scrollbar h-screen lg:relative border-r bg-gray-50">
                <!--                -->
            </div>
            <div class="absolute left-[12rem] h-screen lg:relative no-scrollbar lg:left-0 w-[18rem] overflow-y-scroll border-r bg-white">
                <!--            -->
            </div>
            <Welcome />
        </div>

    </AppLayout>
</template>
