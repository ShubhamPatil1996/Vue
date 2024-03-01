<template>
    <h1>hello from home</h1>
    <h1> {{  data }}</h1>
</template>
<script>

export default{
    name : 'home',
    props:
    {
        data : String
    }
};
</script>
