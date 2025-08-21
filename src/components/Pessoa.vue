<template>
 <div>
  <h2> Essa é a descrição dessa pessoa: {{ nome }}</h2>
  <Info />
  <Form />
 </div>
</template>

<script>
import Form from './Form.vue';
import Info from './Info'

export default {
 name: 'Pessoa',
 components: {
  Info,
  Form
 },
 data() {
  return {
   nome: 'Breno'
  }
 },
  
}
</script>
