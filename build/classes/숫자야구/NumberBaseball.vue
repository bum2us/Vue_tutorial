<template>
    <div>
        <h1>{{result}}</h1>
        <form v-on:submit="onSubmitForm">
            <input ref="answer" maxlength="4" v-model="value" />
            <button>입력</button>
        </form>
    <div>시도: {{}}</div>
    </div>
</template>

<script>
   
</script>

<style>

</style>