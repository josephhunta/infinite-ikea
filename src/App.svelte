<script lang="ts">
  
</script>


<div class="boxgrid">
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
  <button class="box"></button>
</div>


<style lang="scss" scoped>
  .boxgrid{
    height: 500px;
    width: 500px;
    padding: 5px;
    border: 3px solid black;
    background-color: #FFFCF0;
    display: grid;
    grid-template-columns: auto auto auto auto;
    gap: 5px;
    .box{
      border: 1px solid black;
      background-color: #DEB887;
      &:active{
        background-color: #be9e74;
      }
    }
  }
</style>
