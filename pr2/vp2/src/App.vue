<script>

export default{


data(){
return{
text: 'linkу',
href: '/ajax'

}

}

}

</script>
<template>
  <a v-bind:href="href" @click.pevent="">{{ text }}</a>
 

  </template>