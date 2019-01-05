<template>
  <div id="app">
  	
  	<vhead></vhead>
  	
  	<div class="tab">
  		
  		<div class="tab-item">
  			<router-link></router-link>
  		</div>
  		
  		<div class="tab-item">
  			<router-link></router-link>
  		</div>
  		
  		<div class="tab-item">
  			<router-link></router-link>
  		</div>
  		
  	</div>
  	
  	<router-view></router-view>
  	
  </div>
</template>

<script>
	import vhead from './components/head/head';
	
	export default {
	  components: {
	    vhead
	  }
	};
</script>

<style>
html {
  height: 100%;
}

</style>
