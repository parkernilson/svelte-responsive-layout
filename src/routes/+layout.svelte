<script lang="ts">
    import '../app.css'
    import Sidebar from '../components/Sidebar.svelte'
    import Header from '../components/Header.svelte'

    let sidebar: HTMLElement

</script>

<!-- Fixed container for header and sidebar -->
<div class="fixed flex h-full top-0 left-0 right-0 flex-col">
    <!-- Header -->
    <Header bind:sidebar />

    <!-- Sidebar -->
    <Sidebar bind:sidebar />

</div>

<!-- Content -->
<div class="mt-0 sm:mt-12 md:ml-32">
    <slot />
</div>