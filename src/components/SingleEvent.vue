<template>
    <div>
       
            {{event.name}}<br>
            {{event.date}}<br>
            {{event.time}}<br>
            {{event.host}}<br>
            {{event.venue}}<br>
            {{event.type}}<br>
       
        
</div>
</template>

<script>
export default{
    name: 'SingleEvent',
    props:{
        event: Array
}
}

</script>

<style scoped>
h4{
    margin: 2px;
}

div{
    
    padding: 10px;
    color: #ffca02;
    padding: 1em;
    text-align: center;
    width: 80%;
    margin: auto;
    background-color: #004785;

    

}
</style>