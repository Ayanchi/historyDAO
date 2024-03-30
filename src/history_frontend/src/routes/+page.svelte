<script lang="ts">
  import Accordion from "../components/Accordion.svelte";
  import Header from "../components/Header.svelte";
  import "../index.scss";
</script>

<main>
  <Header />
  <h1>About the DAO</h1>
  <Accordion/>
</main>

<slot></slot>

<style>
  main{
    color: aliceblue;
  }
  h1{
    font-size: 30px;
    text-align: center;
  }
</style>