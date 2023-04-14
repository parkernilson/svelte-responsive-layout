<script lang="ts">
    export let sidebar: HTMLElement
</script>

<div class="
    w-full h-12 bg-red-100 hidden sm:flex flex-row-reverse
">
    <button class="md:hidden" on:click={() => {
        sidebar.dataset.active = sidebar.dataset.active === 'true' ? 'false' : 'true'
    }}>Menu</button>
</div>
