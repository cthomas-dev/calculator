<template>
  <div>
    <h1 class="alert alert-primary" role="alert"> Basic Calculator</h1>
    <div class="container bg-dark border calcWidth">
      <div class="row align-items-end text-white text-right displayHeight">
        <div class="col">
          {{ number }}
        </div>
      </div>
      <div class="row">
        <div class="col border bg-light" type="button">
          ac
        </div>
        <div class="col border bg-light" type="button">
          +/-
        </div>
        <div class="col border bg-light" type="button">
          %
        </div>
        <div class="col border bg-warning" type="button">
          &#247;
        </div>
      </div>
      <div class="row">
        <div class="col border bg-light" type="button">
          7
        </div>
        <div class="col border bg-light" type="button">
          8
        </div>
        <div class="col border bg-light" type="button">
          9
        </div>
        <div class="col border bg-warning" type="button">
          *
        </div>
      </div>
      <div class="row">
        <div class="col border bg-light" type="button">
          4
        </div>
        <div class="col border bg-light" type="button">
          5
        </div>
        <div class="col border bg-light" type="button">
          6
        </div>
        <div class="col border bg-warning" type="button">
          -
        </div>
      </div>
      <div class="row">
        <div class="col border bg-light" type="button">
          1
        </div>
        <div class="col border bg-light" type="button">
          2
        </div>
        <div class="col border bg-light" type="button">
          3
        </div>
        <div class="col border bg-warning" type="button">
          +
        </div>
      </div>
      <div class="row">
        <div class="col-6 border bg-light" type="button">
          0
        </div>
        <div class="col border bg-light" type="button">
          .
        </div>
        <div class="col border bg-warning" type="button">
          =
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Calculator',
  props: {
    msg: String
  },
  data: function () {
    return {
      number: 0
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.displayHeight {
  height: 40px;
}
.calcWidth {
  width: 25%;
}
</style>
