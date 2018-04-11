<template>
	<div class="blog">
		<h1>{{title}}</h1>
		<div class="row">
			<div class="col-md-4">
				<div class="card">
					<div class="card-header">
						<h3>Vus.js</h3>
					</div>
					<div class="card-body">
						
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
					</div>
				</div>
			</div>
			<div class="col-md-4">
				<div class="card">
					<div class="card-header">
						<h3>Angular</h3>
					</div>
					<div class="card-body">
						
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
					</div>
				</div>
			</div>
			<div class="col-md-4">
				<div class="card">
					<div class="card-header">
						<h3>React</h3>
					</div>
					<div class="card-body">
						
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
					</div>
				</div>
			</div>
		</div>
	</div>
</template>
<script>
	export default{
		name:'blog',
		data (){
			return{
				title:'Blog'
			}
		}
	}
</script>

<style scoped>
	
</style>