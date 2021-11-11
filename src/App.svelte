<script>
    import { CharityList } from "./CharityList.svelte";

    let name = "Aulia";
    setTimeout(() => {
        name = "Rahmat"
    }, 2000);
</script>

<h1>{name}</h1>
<CharityList />

<style>
    h1{
        font-size: 3em;
        color: yellowgreen;
    }
</style>