<template>
<div class="main">
    <h1>{{ msg }}</h1>
</div>
</template>

<script>
export default {
    name: 'main',
    props: {
        msg: String
    }
}
</script>
