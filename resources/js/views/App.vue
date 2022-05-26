<template>
    <div>
        <h1>
            <PostList/>
        </h1>
    </div>
</template>

<script>
import PostList from'./components/PostList.vue';
export default {
    name: 'App',
    components : {
        PostList,
    }
}
</script>

<style scoped>

</style>
