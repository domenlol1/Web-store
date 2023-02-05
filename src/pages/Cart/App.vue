<template>
    <div>
        <Header />

        <Body />
    </div>
</template>
  
<script>
import Header from "./components/Header.vue";
import Body from "./components/Body.vue";

export default {
    components: { Header, Body },
    data() {
        return {};
    }
}
</script>

<style scoped>

</style>