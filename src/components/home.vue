<template>
<div class="container">
    <p class="title is-spaced">
        Tsundere Database
    </p>
    <p class="subtitle">
        Welcome to the home of all the hard working tsunderes. Select one of the options at the top to get started.
        I-It's not like I am doing this for you, you shitty admiral. 
    </P>
    <p class="subtitle">
        The current TsunDB version is <strong>Kasumi Kai</strong>.
    </p>
    <p class="title is-spaced">
        How do I submit data to the Tsundere Database (TsunDB)?
    </p>
    <p class="subtitle">
        Currently, the only (legitimate) way of sending data to our database is by enabling it in KC3.
        You can go to your KC3改 Settings and enable the option of sending data to the tsunderes. You will help us greatly by doing this. Make sure that you keep your KC3 updated though, as our database rejects submissions from older versions. 
        Also, no, I will not be selling your data, I promise.
    </p>
    <p class="subtitle">
        If you have any other questions or suggestions, feel free to contact me by heading over to the <a href="https://discord.gg/RtSadWM" rel="noopener noreferrer" target="_blank">subreddit discord</a> or the <a href="https://discord.gg/QP6N8QQ" rel="noopener noreferrer" target="_blank"> KC3 discord</a>, you can ask around for @Tsubakura#6815 when you're there. Alternatively, you can always leave a message behind on my <a href="http://kancolle.wikia.com/wiki/Message_Wall:Tsubakura" rel="noopener noreferrer" target="_blank"> wikia wall</a> and I will try to answer it.
    </p>
</div>
</template>

<script>
export default {
    data: function(){
        return{
            mapNamesData: require('./../data/mapNames.json')
        }
    },
    methods:{
        verifyMap(map){
            return (this.mapNamesData.hasOwnProperty(map)) ? true : false;
        }
    }
}
</script>

<style scoped>

</style>
