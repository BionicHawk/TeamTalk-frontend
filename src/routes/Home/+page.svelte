<script lang="ts">
    import AppHeader from '../components/Globals/AppHeader.svelte';
    import type { PageData } from './$types';
    
    export let data: PageData;

    function GoToLogin(event: MouseEvent): void {
        if (event.button === 0) {
            window.open('/', '_self');
        }
    }
</script>

<AppHeader onClickHeaderElement={GoToLogin} />

<main>

</main>

<style>
    main {
        height: max-content;
        margin: 70px 0 0 0;
    }
</style>