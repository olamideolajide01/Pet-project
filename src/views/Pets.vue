<template>
<v-container fluid>   
    <v-row>
      <v-col v-for="(dog, idx) in dogs" :key="idx">
        <DogDetails :item="dog"/>
      </v-col>
    </v-row>
    
    </v-container>
</template>

<script>
import DogDetails from '@/components/DogDetails.vue';
    export default {
       name: 'Dogs',
       components:{
         DogDetails,
       },
       data() {
         return {
          
           dogs: [
             {
               src: 'autralian.jpg',
               title: 'Wolf',
               rating: "4.3 (24)",
               price: ' $560.00',
               breed: 'Wolf',  
               gender: 'Male',  
             },
             {
               src: 'boxer.jpg',
               title: 'Boss',
               rating: '4.5 (8)',
               price: ' $480.99',
               breed: 'boxer',  
               gender: 'Male',  
              
             },
             {
               src: 'brindle.jpg',
               title: 'Wolf',
               rating: '4.0 (41)',
               price: ' $550-$900',
               breed: 'Wolf', 
               gender:'male' 
               
             },
             {
               src: 'brindleSm.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender:'male'
              
             },
             {
               src: 'bull.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'cameo.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'cattledog.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'dog1.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'fish-pet.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'fish1.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'fluf1.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
            
             {
               src: 'fluf2.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'germ.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
            
             
             {
               src: 'houndsm.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'Labrador-retriever.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             
             {
               src: 'military.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'parrot1.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'persian.jpeg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'parrot2.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'platy-fish.png',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'poddle.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'rot1.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'sm.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
             {
               src: 'scat2.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
            
             {
               src: 'scat4.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
            
             {
               src: 'scat5.jpg',
               title: 'Wolf',
               rating: '4.5 (413)',
               price: ' $550-$900',
               breed: 'Wolf',  
               gender: 'Male',  
               age:9,  
               weight: 68,  
               location: 'threed', 
               note: 'Super Friendly',
               status: 'Available',
             },
            
             
            
           ]
         }

       },
      

    }
</script>
