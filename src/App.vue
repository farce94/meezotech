<template>
    <div class="main-container">

        <Header />



        <Footer />

    </div>
</template>

<script>
      import Header from '@/components/Header';
      import Footer from '@/components/Footer';
    export default {
        components: {
            Header,
            Footer
        },

        head() {
            return {
                title: 'Home'
            }
        },
    };
</script>


