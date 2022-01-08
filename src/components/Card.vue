<template>
  <div>
    <b-card
      title=""
      img-alt="Image"
      img-top
      tag="article"
      style="max-width: 24rem; box-shadow: 10px 6px 26px -6px rgba(0,0,0,0.6)"
      class="card-info"
    >
      <b-card-img src="./assets/image-equilibrium.jpg" class="card-img"></b-card-img>

      <div class="text-left text-white my-4">
        <span style="font-size: 32px; font-weight: 600">
          Equilibrium #3429
        </span>

        <div class="my-3" style="font-size: 16px; color: hsl(215, 51%, 70%, 1); font-weight: 200">
          Our Equilibrium collection promotes balance and calm.
        </div>

        <div class="p-2" style="border-bottom: 1px solid rgb(116, 116, 116)">
          <div class="d-flex flex-row justify-content-between">
            <div>
              <span class="d-flex flex-row align-items-center" style="color: hsl(178, 100%, 50%)">
                <img class="mx-2" src="/assets/icon-ethereum.svg" alt="">
                0.041 ETH
              </span>
            </div>
            <div>
              <span class="d-flex flex-row align-items-center text-muted">
                <img class="mx-2" src="/assets/icon-clock.svg" alt="">
                3 days left
              </span>
            </div>
          </div>
        </div>

        <div class="d-flex flex-row align-items-center my-3">
          <div class="col-2">
            <b-img rounded="circle" alt="Circle image" height="35" class="border" src="assets/image-avatar.png"></b-img>
          </div>
          <div class="col-12" style="font-size: 15px">
            <span class="" style="font-weight: 200; color: hsl(215, 51%, 70%, 1)">
              Creation of
            </span>
            <span class="text-white">
              Jules Wyvern
            </span>
          </div>
        </div>
      </div>

      <b-card-text>
      </b-card-text>

    </b-card>
  </div>
</template>

<script>
export default {
  name: 'Card',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 .card-info {
    background-color: hsl(216, 50%, 16%);
    border-radius: 20px;
 }

  .card-img {
    padding: 10px;
    border-radius: 20px;
  }
</style>
