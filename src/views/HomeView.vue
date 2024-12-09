<template>
  <div>
    <!--<el-button>我的按钮</el-button>-->
    <el-table :data="tableData" stripe style="width: 100%">
      <el-table-column prop="date" label="日期"></el-table-column>
      <el-table-column prop="name" label="姓名"></el-table-column>
      <el-table-column prop="address" label="地址"></el-table-column>
    </el-table>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
  },
  data() {
    return {
      tableData: [

      ]
    }
  }
}
</script>
