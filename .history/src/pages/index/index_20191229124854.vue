<template>
  <div>

<i-grid i-class="no-border">
    <i-grid-item> 
        <i-grid-icon>
            <image src="/static/images/1.png" />
        </i-grid-icon>
        <i-grid-label>小黄车</i-grid-label>
    </i-grid-item>
 
   <i-grid-item>
        <i-grid-icon>
            <image src="/static/images/2.png" />
        </i-grid-icon>
        <i-grid-label>Grid</i-grid-label>
    </i-grid-item>

      <i-grid-item>
        <i-grid-icon>
            <image src="/static/images/3.png" />
        </i-grid-icon>
        <i-grid-label>Grid</i-grid-label>
    </i-grid-item>

     <i-grid-item>
        <i-grid-icon>
            <image src="/static/images/1.png" />
        </i-grid-icon>
        <i-grid-label>Grid</i-grid-label>
    </i-grid-item>
</i-grid>
    
  </div>
</template>

<script>


export default {
  data () {
    return {
    
    }
  },

  

  methods: {
   

  },

  created () {
 
  }
}
</script>

<style scoped>
 div >>> .no-border{
  border-width:0pt;
}
div >>> .split{
  margin-bottom:10pt;
}
</style>
