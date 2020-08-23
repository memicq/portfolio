<template>
	<div class="wrapper">
		<el-dropdown>
			<i class="el-icon-setting" style="margin-right: 15px;"></i>
			<el-dropdown-menu slot="dropdown">
				<el-dropdown-item>View</el-dropdown-item>
				<el-dropdown-item>Add</el-dropdown-item>
				<el-dropdown-item>Delete</el-dropdown-item>
			</el-dropdown-menu>
		</el-dropdown>
		<span>Akiyuki Kamiura</span>
	</div>
</template>

<style>
  .el-header {
    background-color: #6E7783;
    color: white;
    text-align: center;
    line-height: 56px;
  }

  .el-header i {
	  color: white;
  }
</style>
