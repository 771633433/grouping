<template>
  <div class="hello">
        <div id="example"> 
   	   	   <div class="demo-section k-content"> 
    	   		<h4>Customers</h4> 
    	   		<input id="customers" style="width: 100%;"> 
   			</div> 
   		</div>
  </div>
</template>

<script>
 $(document).ready(function() {
                    $("#customers").kendoDropDownList({
                        dataSource:{
                          data:["James","Wade","Paul"]
                        },
                        animation:false
                    });
                });
export default {
  name: 'hello',
  data () {
    return {
   
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
@import '/static/style/examples-offline.css';
@import '/static/style/kendo.common.min.css';
@import '/static/style/kendo.dataviz.default.min.css';
@import '/static/style/kendo.dataviz.min.css';
@import '/static/style/kendo.default.min.css';
@import '/static/style/kendo.rtl.min.css';
</style>
