<template>
	<div id="f1">
		<p>{{name}}</p>
		<p>{{age}}</p>
		<p>{{fun()}}</p>
		<p>hello</p>
	</div>
</template>
<script>
	export default{
		data(){
			return{
			name:'sam',
			age:18,
			}
			
		},
		methods:{
			fun:function(){
				return this.name + ' good!!';
			}
		}
	
	}
</script>


