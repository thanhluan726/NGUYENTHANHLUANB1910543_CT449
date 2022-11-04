<script>
export default{
    props:{
        contact: { type: Object, required: true },
    } , 
};
</script>
<template>
    <div>
        <div class="p-1">
            <strong></strong>
            {{ contact.name }}
        </div>
       
        <div class="p-1">
            <strong>Date:</strong> 
            {{ contact.address }}
        </div>
        <div class="p-1">
            <strong>Content:</strong> 
            {{ contact.phone }}
        </div>
       
    </div>
</template>