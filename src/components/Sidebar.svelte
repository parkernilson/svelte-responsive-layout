<script lang="ts">
    export let sidebar: HTMLElement
    
</script>

<div bind:this={sidebar} data-active="false" class="
    w-32 flex-grow bg-blue-100 hidden sm:block
    transition-transform duration-300 ease-in-out
    data-[active=false]:translate-x-[-100%] data-[active=true]:translate-x-0 
    md:data-[active=false]:translate-x-0 md:transition-none
">
    <h1 class="text-lg">Sidebar</h1>
</div>