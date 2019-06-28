<template>
    <div>课程编辑
        <div>{{sysId}}</div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            sysId:'',
        }
    },
    created(){
        this.sysId = this.$route.params.sysId
    }
}
</script>

<style>
</style>