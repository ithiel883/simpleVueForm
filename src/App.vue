<template>
<Header />
  <Form />
  <Button />
</template>

<script>
import Form from './components/Form'
import Button from './components/Button'
import Header from './components/Header'

export default {
  name: 'App',
  components: {
    Form,
    Button,
    Header
  }
}
</script>

<style>
#app {
  
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
 
</style>
