<template>
    <div>
        <div class="hold-transition sidebar-mini layout-fixed">
            <div class="wrapper">
                <Navbar />
                <SidebarAdmin />
                <div class="content-wrapper">
                    <router-view />
                </div>
                <Footer />
            </div>
        </div>
    </div>
</template>
<script>
import Footer from '../../layout/Footer.vue';
import Navbar from '../../layout/Navbar.vue';
import SidebarAdmin from '../../layout/SidebarAdmin.vue';

export default {
    data(){
        return{

        }
    },
    created(){

    },
    components:{
        Footer,
        Navbar,
        SidebarAdmin,
    }
}
</script>