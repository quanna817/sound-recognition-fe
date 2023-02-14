<template>
  <!-- <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous"> -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <div class="navbar">

    <div class="dropdown">
      <button class="dropbtn">Sound Analysis
        <i class="fa fa-caret-down"></i>
      </button>
      <div class="dropdown-content">
        <a href="#statistics">Statistics</a>
        <a href="#upload">Upload</a>
      </div>
    </div>
    <div class="dropdown">
      <button class="dropbtn">Classification Sound configuration
        <i class="fa fa-caret-down"></i>
      </button>
      <div class="dropdown-content">
        <a href="#urbansound">URBANSOUND8K dataset (10 CLASSSES)</a>
        <a href="#esc">ESC-50 dataset (40 CLASSSES)</a>
      </div>
    </div>
    <div class="dropdown">
      <button class="dropbtn">Word matching configuration
        <i class="fa fa-caret-down"></i>
      </button>
      <div class="dropdown-content">
        <a href="/registration-word">Registration word for recognition (Add/Edit/Remove)</a>
      </div>
    </div>
    <div class="btn-info">
      <a href="#user-info">User information</a>
      <a href="#about">About us</a>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar {
  overflow: hidden;
  background-color: #61b771;
}

.navbar a {
  float: left;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.dropdown {
  float: left;
  overflow: hidden;
}

.dropdown,.dropbtn {
  font-size: 16px;
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}
.navbar,a:hover,.dropdown:hover,.dropbtn {
  background-color: #aad1a8;
}
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #aad1a8;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}
.dropdown:hover .dropdown-content {
  display: block;
}
.btn-info {
  margin-left: 85%;
  margin-top: 15px;
}
</style>
