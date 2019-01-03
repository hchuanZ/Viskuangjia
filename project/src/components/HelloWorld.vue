<template>
  <div>
    <syou-pie-chart
          class="pie-chart"
        />

       <syou-gauge-chart 
        id='index-1'
       right='550' 
        container="gauge1" 
        class="gauge-chart" 
        value='100'
        name='签约评估得分'
      />
      <syou-gauge-chart
        id='index-2'
        right='800'
        container="gauge2" 
        class="gauge-chart"
        value='90'
        name='达标评估得分'
      />
  </div>
</template>

<script>

//import SyouMapboxView from './SyouMapboxView.vue'
import SyouPieChart from './SyouPieChart.vue'
//import SyouRadarChart from './SyouRadarChart'
//import SyouBubbleChart from './SyouBubbleChart.vue'
import SyouGaugeChart from './SyouGaugeChart.vue'
export default {
  name: 'HelloWorld',
  data () {
    return {
      
    }
  },
  components:{
    //SyouMapboxView
    SyouPieChart,
    //SyouRadarChart
   //SyouBubbleChart
   SyouGaugeChart
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
