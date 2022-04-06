<template>
    <div>
        <h1>About</h1>
        <p>This is the about page</p>
    </div>
</template>

<script>
export default {
    head() {
        return {
            title: 'About Page',
            meta:[
                {
                hid: 'description',
                name: 'description',
                content: 'This is the about page',
                },
            ]
        };
    },
}
</script>  
<style>

</style>