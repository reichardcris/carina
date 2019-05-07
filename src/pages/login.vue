<template >
  
  <div class="row justify-center q-mt-lg">
  		<div class="col-lg-4 col-md-4 col-sm-6 col-xs-11 ">
		    <div class=" gutter-md  ">
		        <div class="col text-center">
		                <h2 class="q-title">Log In</h2>
		            </div>
		        <div class="col">
		            <q-input v-model="loginData.email" type="email" float-label="Email"></q-input>
		        </div>
		        <div class="col">
		            <q-input v-model="loginData.password" @keyup.enter.native="login" type="password"  :readonly="false" float-label="Password"></q-input>
		        </div>
		        <div class="col">
		            <q-btn @click="login"  icon="fa fa-sign-in-alt" label="Log In" color="primary" 	 class="full-width"></q-btn>
		        </div>
		       <!--  <div class="col">
		            <q-btn @click="isPasswordReset=!isPasswordReset"  label="Forgot Password" :outline="true" color="primary" class="full-width"></q-btn>
		        </div> -->
		    </div>
		</div>
  </div>

</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex',
  data:function(){
  	return {
  		loginData:{email:'',password:''},
  	}
  },
  methods:{
  	login:function(){

  	}
  }
}
</script>
