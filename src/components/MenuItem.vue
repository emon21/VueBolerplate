
// Menu Item

<script>
import { defineComponent } from 'vue'
 
 export default defineComponent({})

</script>

<template>
   <div class="menu">
      <ul>
         <li> <a href="#">Home</a></li>
         <li> <a href="#">About US</a></li>
         <li> <a href="#">News</a></li>
         <li> <a href="#">Blog</a></li>
         <li> <a href="#">Service</a></li>
         <li> <a href="#">Protfolio</a></li>
         <li> <a href="#">Contact US</a></li>
      </ul>
   </div>
</template>


<style>
.menu{
   /* background-color: bisque; */
   width: 120%;
   /* margin: 0 auto; */
   margin-bottom: 50px;
}
ul {
   list-style: none;
   padding: 0;
   margin: 0;
   /* display: flex; */
   /* flex-direction: row; */
   /* display: inline-block; */
}

ul li {
   /* padding: 10px; */
   margin: 0 2px;
   background: tomato;
   /* background: blue; */
   display: inline-block;
   /* display: inline-flex; */
   border-top-left-radius: 5px;
   border-bottom-right-radius: 5px;
   /* border: 2px solid blue; */
}

ul li:last-child {
   /* border-right: none; */

   /* border-top-left-radius: 0; */
   /* border-top-right-radius: 5px; */
}

ul li a {
   text-decoration: none;
   color: black;
   padding: 10px;
   font-size: 20px;
   display: inline-block;
   text-align: center;
   /* display: block; */
   transition: all 0.5s ease-in-out;
   /* padding-top: 25px; */
}

ul li a:hover {
   color: white;
   /* padding: 10px; */
   /* transform: translate(0,5px); */
   transform: scale(1.2);
   background-color: transparent;
}


</style>