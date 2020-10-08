<template>
  <div>
    <h3>A single user with ID: {{$route.params.id}}</h3>
  </div>
</template>
<script>
export default {
  validate(data){
    // console.log(data.params);
    // return /^\d$/.test(data.params.id);
    return true;
  },
  layout:'users'
}
</script>
