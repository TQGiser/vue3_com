<template>
    <div>
        {{msg}}
    </div>
</template>

<script>
import {useStore} from 'vuex'
import {reactive, toRefs} from 'vue'
    export default {
        setup(){
            const store = useStore()
            const state = reactive({
                    msg:null
            })
                
            state.msg = store.state.value2
        return {

            ...toRefs(state)
        }
        }
        
    }
</script>

<style lang="scss" scoped>

</style>
