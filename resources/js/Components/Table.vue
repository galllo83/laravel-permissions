<script setup></script>
<template>
    <div class="relative overflow-x-auto shadow-md sm:rounded-lg">
        <table
            class="w-full text-sm text-left text-gray-700 dark:text-gray-400"
        >
            <thead
                class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400"
            >
                <slot name="header"></slot>
            </thead>
            <tbody>
                <slot></slot>
            </tbody>
        </table>
    </div>
</template>
<style>
tbody tr:nth-of-type(odd) {
    
    background-color: rgb(107 114 128);
}

tbody tr:nth-of-type(even) {
    
    background-color: rgb(75 85 99);
}
</style>
