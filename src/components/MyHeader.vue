<template>
    <div>
            <h1>{{university}}</h1>
            <h3>{{office}}</h3>
            <h3>{{subtitle}}</h3>

    </div>

</template>

<script>

export default{ // Exporting Default Object
    name: 'MyHeader',
    props:{ 

        university:String,
        office:String,
        subtitle: String
    }
}

</script>

<style scoped>
div{
    text-align: center;
}
</style>