<template>
    <h1>this is the users page {{$route.params.id}}</h1>
</template>

<script>
export default {
    validate (data) {
        return /^\d+$/.test(data.params.id)
    }
}
</script>