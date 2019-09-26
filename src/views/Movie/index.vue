<template>
  <div id="main">
        <Header title="我的Movie" />
        <div id="content">
            <Login />
        </div>
        <TabBar />
    </div>
</template>

<script>
import Header from "@/components/Header";
import TabBar from "@/components/TabBar";
export default {
    name : 'Movie',
    components : {
        Header,
        TabBar,
    }
};
</script>

<style>
