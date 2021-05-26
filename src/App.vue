<template>
  <div>
      <h1>{{ value1 }}</h1>
      <h1>{{ value2 }}</h1>
      <h1>{{ value3 }}</h1>
      <h1>{{ value4 }}</h1>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value1: "Everything's mental. You create your reality with your thoughts.", 
      value2: "To be a CHAMPION you have to believe in youself when nobody else will..",
      value3: "If you are afraid of failing, you won't get very far!",
      value4: "To Do Very Hard Things Or For Something That Seems Like Sort Of An Impossible Goal Is To Just Steadily Broaden Your Comfort Zone Over Time To Basically Consistently Do Things That Are Slightly Harder For You, In The Right Direction Not Necessarily Specifically Towards That Goal But Sort Of Keep Broadening Yourself Until Eventually It Seems Possible.",
      
      };
  }
};
</script>

<style  lang="scss" scoped>

  h1 {
      padding-left: 0;
  }

</style>



