<template lang="html">
    <div>
        <Heador/>
        <Islider/>
      
        <Footor/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Islider from './islider.vue'
import Footor from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
export default {
	components:{
		Heador,
		Islider,
		Footor,
		Navbar,
	},
}
</script>
