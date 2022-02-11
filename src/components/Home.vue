<template>
    <div>

            <h1>Hello Welcome To Home</h1>
    </div>
</template>



<script>
export default {
    
    name:'Home',


      mounted()
    {   
            let user = localStorage.getItem('user-info');

            if(!user)
            {
                 this.$router.push({name:'SignUp'});
            }

    }


}
</script>