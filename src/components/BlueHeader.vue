<template>
    <div>
        <header class="head">
            <img class="head-logo" src="../../public/SUEZ NWS_RGB_BLUE-BG-01.png" alt="suez logo" width="300" >
            <div class="head-headers">
                <h1 class="head-headers-title">Monthly REX Report</h1>
                <h2 class="head-headers-sub-title">{{ sub_title }}</h2>
                <p class="head-headers-des">Reporting period: {{ date }}</p>
            </div>
        </header>
    </div>
</template>

<script>
export default {
    name: 'BlueHeader',
    data() {
        return {
            sub_title: 'Incident Report Summary',
            date: '2020 May'
        }
    },
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>




.head {
    position: relative;
    width: 100%;
    height: 200px;
    background-color: rgb(40, 34, 75);
}

.head-logo {
    position: absolute;
    right: 0;
    top: 50%;
    transform: translate(0, -50%);
}

.head-headers {
    /* border: 1px solid white; */
    position: absolute;
    left: 1.2em;
    top: 50%;
    transform: translate(0, -25%);

    color: #fff;
}

.head-headers-title {
    font-size: 1.6em;
    margin: 0;
    text-align: left;
    margin-bottom: 0;
}

.head-headers-sub-title {
    font-size: 1em;
    text-align: left;
    font-weight: bold;
    margin-bottom: 0;
    margin-top: 1em;

}

.head-headers-des {
    margin-top: 0.2em;
    font-size: 0.8em;

    text-align: left;
}


</style>
