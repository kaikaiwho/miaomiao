<template>
    <div>
        <Header title="影院"/>
        hello Cinema
        <TabBar />
    </div>
</template>

<script>
import Header from '@/components/Header'
import TabBar from '@/components/TabBar'
export default {
    name : 'Cinema',
    components : {
        Header,
        TabBar
    }
}
</script>

<style lang="stylus" scoped>

</style>