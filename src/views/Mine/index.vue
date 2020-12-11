<template>
    <div>
        <Header title="我的"/>
        hello Mine
        <TabBar />
    </div>
</template>

<script>
import Header from '@/components/Header'
import TabBar from '@/components/TabBar'
export default {
    name : 'Mine',
    components : {
        Header,
        TabBar
    }
}
</script>

<style lang="stylus" scoped>

</style>