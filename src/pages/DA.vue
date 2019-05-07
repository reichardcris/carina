<template>
  <div class="row justify-center q-mt-lg">
  		<div class="col-12" style="text-align:center">
  			<h4>Register Farmer</h4>
  		</div>
  		<div class="col-lg-4 col-md-4 col-sm-6 col-xs-11 q-mr-lg">
		    <div class=" gutter-md  ">
		        <div class="col text-center">
		                <h2 class="q-title">Farmer Information</h2>
		            </div>
		        <div class="col">
		            <q-input v-model="loginData.email" type="text" float-label="First Name"></q-input>
		        </div>
		        <div class="col">
		            <q-input v-model="loginData.password" type="text"  :readonly="false" float-label="Last Name"></q-input>
		        </div>
		        <div class="col">
		            <q-input v-model="loginData.password" type="text"  :readonly="false" float-label="Middle Name"></q-input>
		        </div>
		        <div class="col">
		            <q-input v-model="loginData.password" type="text"  :readonly="false" float-label="Suffix"></q-input>
		        </div>
		        <div class="col-12">
		            <q-btn @click="register"  icon="fa fa-sign-in-alt" label="Log In" color="primary" 	 class="full-width"></q-btn>
		        </div>
		       <!--  <div class="col">
		            <q-btn @click="isPasswordReset=!isPasswordReset"  label="Forgot Password" :outline="true" color="primary" class="full-width"></q-btn>
		        </div> -->
		    </div>
		</div>
		<div class="col-lg-4 col-md-4 col-sm-6 col-xs-11 ">
		    <div class=" gutter-md  ">
		        <div class="col text-center">
		                <h2 class="q-title">Farmer Commodity</h2>
		            </div>
		        <div class="col">
		            <q-input v-model="loginData.email" type="text" float-label="Crops Name"></q-input>
		        </div>
		        <div class="col">
		            <q-input v-model="loginData.password" type="text"  :readonly="false" float-label="No. of Crops"></q-input>
		        </div>
		        <div class="col">
		            <q-input v-model="loginData.password" type="text"  :readonly="false" float-label="Market Outlet"></q-input>
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
  }
}
</script>
