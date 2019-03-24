<template>
	<el-row :gutter="12">
		<el-col :span="6">
			<el-card shadow="always">
				总是显示
			</el-card>
		</el-col>
		<el-col :span="6">
			<el-card shadow="always">
				总是显示
			</el-card>
		</el-col>
		<el-col :span="6">
			<el-card shadow="always">
				总是显示
			</el-card>
		</el-col>
		<el-col :span="6">
			<el-card shadow="always">
				总是显示
			</el-card>
		</el-col>
	</el-row>
</template>

<script>
	export default {
		data() {
			return {
				users: [],
				total: 0,
				page: 1

			}
		},
		methods: {

		},
		mounted() {
			this.getUsers();
		}
	}

</script>

<style scoped>

</style>