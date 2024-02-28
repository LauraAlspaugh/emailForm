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
    <section class="row visit-section mb-3">
      <div class="col-12 text-center">
        <p class="fs-3 mb-3 p-4 newsletter">From me to you.</p>
        <p class="fs-5 p-4 newsletter">Hey Friend. Welcome to the Journey.</p>
        <button class="btn visit-button p-3 mb-3">Visit My Site</button>
      </div>
    </section>
    <section class="row justify-content-center visit-section mb-3">
      <div class="col-12">
        <p class="fs-4 text-center newsletter p-4">What's Happening</p>
      </div>
      <div class="col-4 mb-3">
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laboriosam error tenetur eos dolorem harum et minus
          atque repudiandae alias quis quas possimus eveniet expedita, accusamus nihil rem omnis a illum ipsa officiis
          amet in. Eum alias sint repellendus nihil? Quam vitae aperiam, vel id quis omnis maiores ducimus laboriosam ab!
        </p>
      </div>
      <div class="col-4 mb-3">
        <img class="img-fluid second-image"
          src="https://images.unsplash.com/photo-1660849337659-2f2c9fdbb0e2?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8YWVzdGhldGljJTIwYmlrZXxlbnwwfHwwfHx8MA%3D%3D"
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
  color: #784212;
}

img {
  height: 500px;
  width: 60%;
  position: center;
  object-fit: cover;
}

.second-image {
  object-fit: cover;
  position: center;
  width: 60%;
  height: 400px;
}

.visit-button {
  background-color: #BFC9CA;
  color: white;
  border-radius: 0;
}

.visit-section {
  border-bottom: 2px solid #BFC9CA;
}
</style>
