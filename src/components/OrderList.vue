<template>
  <div>
    <md-list>
      <md-subheader>04/11 Wed</md-subheader>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="1" />
        <span class="firstRow md-list-item-text ">Order x11201 </span>
        <span class="firstRow material-icons ">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="2" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
      <md-checkbox v-model="order" value="3" />
      <span class="md-list-item-text">Order x11201 </span>
      <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="4" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="5" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="6" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>
      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="7" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="8" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>

    </md-list>

    <md-list>
      <md-subheader>05/11 Thursday</md-subheader>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="9" />
        <span class="firstRow md-list-item-text ">Order x11201 </span>
        <span class="firstRow material-icons ">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="10" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="11" />
        <span class="md-list-item-text">Order x11201 </span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="12" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="13" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="14" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>
      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="15" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="16" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>

    </md-list>

    <md-list>
      <md-subheader>06/11 Friday</md-subheader>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="117" />
        <span class="firstRow md-list-item-text ">Order x11201 </span>
        <span class="firstRow material-icons ">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="18" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="19" />
        <span class="md-list-item-text">Order x11201 </span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="20" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="21" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="22" />
        <span class="md-list-item-text">111Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>
      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="23" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="24" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>

    </md-list>

    <md-list>
      <md-subheader>07/11 Saturday</md-subheader>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="25" />
        <span class="firstRow md-list-item-text ">Order x11201 </span>
        <span class="firstRow material-icons ">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="26" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="27" />
        <span class="md-list-item-text">Order x11201 </span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="28" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="29" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="30" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>
      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="31" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="32" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>

    </md-list>

    <md-list>
      <md-subheader>08/11 Sunday</md-subheader>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="33" />
        <span class="firstRow md-list-item-text ">Order x11201 </span>
        <span class="firstRow material-icons ">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="34" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="35" />
        <span class="md-list-item-text">Order x11201 </span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="36" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="37" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="38" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>
      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="40" />
        <span class="firstRow md-list-item-text">Order x11202</span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>
      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="39" />
        <span class="md-list-item-text">Order x11201 </span>
        <span class="material-icons">lock</span>
      </md-list-item>



    </md-list>

    <md-list>
      <md-subheader>09/11 Monday</md-subheader>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="41" />
        <span class="firstRow md-list-item-text ">Order x11201 </span>
        <span class="firstRow material-icons ">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="42" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="43" />
        <span class="md-list-item-text">Order x11201 </span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="sou44nd" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="45" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="46" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>
      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="47" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="48" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>

    </md-list>

    <md-list>
      <md-subheader>10/11 Tuesday</md-subheader>
      <md-list-item class="unlocked">
        <md-checkbox class="firstRow" v-model="order" value="49" />
        <span class="firstRow md-list-item-text ">Order x11201 </span>
        <span class="firstRow material-icons ">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="50" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>
      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="51" />
        <span class="md-list-item-text">Order x11201 </span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="unlocked">
        <md-checkbox v-model="order" value="52" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock_open</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="53" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked1">
        <md-checkbox v-model="order" value="54" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>
      <md-list-item class="locked2">
        <md-checkbox v-model="order" value="55" />
        <span class="firstRow md-list-item-text">Order x11201 </span>
        <span class="firstRow material-icons">lock</span>
      </md-list-item>

      <md-list-item class="locked2" style="color: white">
        <md-checkbox v-model="order" value="56" />
        <span class="md-list-item-text">Order x11202</span>
        <span class="material-icons">lock</span>
      </md-list-item>

    </md-list>
  </div>
</template>

<script>
export default {
  name: 'OrderList',
  props: {
    msg: String
  },
  data: () => ({
    order: []
  })
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.md-subheader{
  border: 1px solid #000000;
  font-size: 16px;
  font-weight: bold;
  border-collapse:collapse;
  border-spacing:0;
}
.md-list {
  width: 14%;
  max-width: 100%;
  display: inline-block;
  vertical-align: top;
  border-right: 0px solid #000000;
}
.md-list-item{
  border: 0px solid #000000;
}
a {
  color: #42b983;
}
.md-subheader{
  text-align: center;
  display: grid;
}
.unlocked{
  background-color: green;
  border: 1px solid #000000;
  border-top: 0px;
}
.locked1{
  background-color: orange;
  border: 1px solid #000000;
  border-top: 0px;
}
.locked2{
  background-color: red;
  border: 1px solid #000000;
  border-top: 0px;
}
.firstRow{
  color: white;
}
</style>
