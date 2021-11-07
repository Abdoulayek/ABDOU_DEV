<template>

    <ul>
       <li class="active"><a href="Accueil.vue">Accueil</a></li>
  <li class="active"><a href="mailto:abdoulayekante863@gmail.com">Nous contacter</a></li>
    </ul>
     <img alt="Vue logo" src="./abdou.png">
<div>
    
    
    <h2>Abdou_Dev est votre société de référence dans la conception de sites web et d'applications mobiles.<br />
    Notre équipe est composée de développeurs passionés, expérimentés et amoureux du web.
    <br />
    Contactez-nous et votre projet devient réel !</h2>
    <hr />
    <ol><h1>Nos services:</h1>
    
        <li>Rédaction de cahiers de charges</li>
        <li>Conception de sites web</li>
        <li>Conception d'applications mobiles</li>
        <li>Hébergement et publication</li>
        <li>Référencement SEO</li>
    </ol>
    

</div>
    
   
</template>

<script>
export default {
  name: 'Accueil'
}
</script>

<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    width: 200px;
    margin-top: -50px;
    background-color: #f1f1f1;
}


li a {
    display: block;
    color: #000;
    padding: 8px 0 8px 16px;
    text-decoration: none;
}

/* Change the link color on hover */
li a:hover {
    background-color: #555;
    color: white;
}
.active {
    background-color: #4caf4f3a;
    color: white;
}
img{
    width: 400px;
    height: 400px;
    margin-top: -100px;
}
p{
    font-size: 20px;
}
hr {
    display: block;
    height: 1px;
    border: 0;
    border-top: 1px solid #ccc;
    margin: 1em 0;
    padding: 0;
}
ol li{
    list-style: none;
    font-size: 18px;
    margin: 20px;
}
div{
    margin-top: -100px;
}
</style>




