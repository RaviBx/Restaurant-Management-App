<template>
    <div>

        <h1>Login</h1>

   <div class="register">

            <input type="text" v-model="name" placeholder="Enter Name" />
            <input type="text" v-model="email" placeholder="Enter Email" />
            <input type="password" v-model="password" placeholder="Enter Password" />

            <button v-on:click="signUp">Sign Up</button>

            <p>
                <router-link to="/login">Login</router-link>
            </p>

    </div>

    </div>
</template>






<script>
export default {

    name:'Login'
    
}
</script>