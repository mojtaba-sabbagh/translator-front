<template>
  <div class="flex flex-col items-center mt-10">
    <div>
      <textarea class="border-2 p-2" id="source" name="source" 
        rows="4" cols="50" :placeholder="source"></textarea>
    </div>
    <div>
      <button> <img src="~/assets/images/nn.png"/></button>
    </div>
    <div>
      <textarea class="border-2 text-right p-2" id="source" name="source" 
        rows="4" cols="50" :placeholder="destination"></textarea>
    </div>
  </div>
</template>


<script>
export default {
  name: 'IndexPage',
  data() {
          return {
            source: 'English',
            destination: 'فارسی'
          }
        }
}
</script>
