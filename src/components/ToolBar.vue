<template>
  <div class="page-container md-layout-column">
  <md-toolbar>
<ul class="ToolBarUl">

  <li class="lastLi">
    <md-button class="md-icon-button" @click="showNavigation = true">
      <md-icon>menu</md-icon>
    </md-button>
  </li>
  <li>
    <md-checkbox v-model="string" value="1">Auckland</md-checkbox>
    <md-checkbox v-model="string" value="2">Otahuhu</md-checkbox>
    <md-checkbox v-model="string" value="3">Hamilton</md-checkbox>
    <md-checkbox v-model="string" value="4">ChristChurch</md-checkbox>
    <md-checkbox v-model="string" value="5">Owner Truck</md-checkbox>
    <md-checkbox v-model="string" value="6">Curiour</md-checkbox>
    <md-checkbox v-model="string" value="7">Truck</md-checkbox>
  </li>
  <li>
    <md-field>
      <label for="font">Action</label>
    <md-select v-model="Action" name="Action" id="Action">
      <md-option value="Action1">Action1</md-option>
      <md-option value="Action2">Action3</md-option>
      <md-option value="Action3">Action3</md-option>
    </md-select>
      </md-field>
  </li>
  <li>
    <md-field>
      <label>Search</label>
      <md-input v-model="search"></md-input>
    </md-field>
  </li>

</ul>
    </md-toolbar>
    <md-drawer :md-active.sync="showNavigation">
      <md-toolbar class="md-transparent" md-elevation="0">
        <span class="md-title">Navigation</span>
      </md-toolbar>

      <md-list>
        <md-list-item href="https://google.com" target="_blank">Link</md-list-item>
        <md-list-item href="https://google.com" target="_blank">Link</md-list-item>
        <md-list-item href="https://google.com" target="_blank">Link</md-list-item>
        <md-list-item href="https://google.com" target="_blank">Link</md-list-item>
        <md-list-item href="https://google.com" target="_blank">Link</md-list-item>
      </md-list>
    </md-drawer>
  </div>
</template>

<script>
export default {
  name: 'ToolBar',
  props: {
    msg: String
  },
  data: () => ({
    string: [],
    indeterminate: true,
    Action: 'Action',
    search:null,
    showNavigation: false
  })
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.ToolBarUl{
  display: flex;
  flex-flow: row nowrap;
  justify-content: center;
  width: 100%;
  padding-left: 0px;
}
.ToolBarUl li{
  list-style: none;
  border: 0px solid #2c3e50;
  text-align: left;
  line-height: 2px;
  height: 100px;
  width: 30%;
  margin: 0 30px;
}
.md-checkbox {
  margin: 5px 10px 5px 0;
}
a {
  color: #42b983;
}

.ToolBarUl .lastLi{
  list-style: none;
  border: 0px solid #2c3e50;
  text-align: left;
  line-height: 2px;
  padding: 2px;
  height: 100px;
  width: 5%;
  margin: 0 2px;
  padding-left: 0px;
}


</style>
