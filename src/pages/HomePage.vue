<template>
  <div class="container-fluid">
    <section class="row">
      <div class="col-12 p-4">
        <p class="fs-1 newsletter text-center mb-0">January</p>
        <p class="fs-1 newsletter text-center p-0 mt-0">Newsletter.</p>
      </div>
    </section>
    <section class="row">
      <div class="col-12 text-center">
        <img class="img-fluid"
          src="https://images.unsplash.com/photo-1571769710016-43cbfbfcf02d?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OXx8YWVzdGhldGljJTIwYmlrZXxlbnwwfHwwfHx8MA%3D%3D"
          alt="">
      </div>
    </section>
  </div>
</template>

<script>
export default {
  setup() {
    return {

    }
  }
}
</script>

<style scoped lang="scss">
.newsletter {
  color: #BDC3C7;
}

img {
  height: 500px;
  width: 60%;
  position: center;
  object-fit: cover;
}
</style>
