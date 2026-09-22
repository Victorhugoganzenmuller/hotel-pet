<script setup>
    import { RouterLink } from 'vue-router';
</script>

<template>
    <nav>
        <div class="fles-column nav-pills gap-1">
            <RouterLink to="/pets">
                <i class="fa-solid fa-dog"></i>
            </RouterLink>
            <RouterLink to="/pets/novo">
                <i class="bi bi-plus-circle me"></i>
                Pets
            </RouterLink>
        </div>
    </nav>
</template>