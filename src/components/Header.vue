<template>
    <div>
        <b-nav tabs>
            <b-nav-item enabled>Home</b-nav-item>
            <b-nav-item enabled>About Us</b-nav-item>
            <b-nav-item disabled>Counter: {{ numCorrect }}/{{ numTotal }}</b-nav-item>
        </b-nav>
    </div>
</template>

<script>
    export default {
        props: [
            'numCorrect',
            'numTotal'
        ]
    }
</script>
