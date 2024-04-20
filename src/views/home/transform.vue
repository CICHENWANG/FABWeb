<template>
    <fv-text-box
        v-show="step === 0"
        v-model="content"
        :placeholder="local(`请输入翻译内容`)"
        borderWidth="2"
        :revealBorder="true"
        background="whitesmoke"
        :border-radius="6"
        style="width: 80%; max-width: 375px; height: 40px; margin-top: 45px; flex-shrink: 0"
    ></fv-text-box>
</template>
<script>

export default {

    data(){
        return{
            content:"123",
            step: 0,
        }
    },
    methods(){
    }
}
</script>