<script>
import Logo from '../components/Logo.vue';
import Filter from '../components/Filter.vue';
import Contacts from '../components/Contacts.vue';
import Basket from '../components/Basket.vue';
import Presentation from '../components/Presentation.vue';
import Stocks from '../components/Stocks.vue';
import Seasons from '../components/Seasons.vue';
import Gifts from '../components/Gifts.vue';
import Forum from '../components/Forum.vue';
import Map from '../components/Map.vue';

export default {
    name: 'Main',
    components: {
    Logo,
    Filter,
    Contacts,
    Basket,
    Presentation,
    Stocks,
    Seasons,
    Gifts,
    Forum,
    Map
},
}

</script>

<template>
    <main class="main">
        <section class="main__filter">
            <Logo />
            <Filter />
            <Contacts />
            <Basket />
            <Presentation />
            <Stocks />
            <Seasons />
            <Gifts />
            <Forum />
            <Map />
        </section>
    </main>
</template>