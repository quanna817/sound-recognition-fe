<template>
  <Navbar></Navbar>
  <h1>đây là upload</h1>
  <div class="upload-box">
    <div class="row">
      <div class="col-lg-12">
        <div style="width:40%; margin:25px auto; padding: 10px;" class="new-file">
          <h1 style="text-align: center; padding-bottom: 3rem;">Upload New Sound File</h1>
            <form @submit.prevent="uploadFile">
              <div class="form-group">
                <input type="file" ref="fileInput" accept="audio/*" style="width:220px; text-align: center;">
              </div>
              <div class="custom-control custom-switch public-switch">
                <input type="checkbox" id="customSwitch1" name="public" checked>
                <label class="custom-control-label" for="customSwitch1"><strong>Make Public</strong></label>
              </div>
              <div>
                <button class="btn btn-primary upload-btn">Classify!</button>
              </div>
            </form>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Up-load',
  components: {
    Navbar
  },
  data () {
    return {
      public: true
    }
  }
  // methods: {
  //   async uploadFile() {
  //     const input = this.$refs.fileInput
  //     const file = input.files[0]

  //     // do something with the file here
  //     // ex: upload to server, etc.
  //   }
  // }
}
</script>

<style>
.dropdown-menu{
  margin-top: 20px;
}
</style>
