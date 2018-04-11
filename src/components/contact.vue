<template>
	<div class="contact">
		<h1>{{title}}</h1>
		
		 <div class="contact">
		 	<form>
		 		<div class="form-group">
		 			<div class="input-group-prepend">
		 				
		 				<input type="text" class="form-control" name="">
		 			</div>
		 			<div class="input-group-prepend">
		 				
		 				<input type="text" class="form-control" name="">
		 			</div>
		 			<div class="input-group-prepend">
		 			
		 				<textarea class="form-control">
		 					
		 				</textarea>
		 			</div>
		 			<button class="btn btn-primary btn-block">Submit</button>
		 		</div>
		 	</form>
		 </div>
	</div>
</template>
<script>
	export default{
		name:'blog',
		data (){
			return{
				title:'contact'
			}
		}
	}
</script>

<style scoped>
.contact form{
	max-width: 40em;
	margin: 2em auto;
}
.contact form .form-control{
	margin-bottom: 1em;
}
.contact form textarea{
	min-height: 20em;
}	
</style>