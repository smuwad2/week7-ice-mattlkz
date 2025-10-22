<script>
    export default { 
        // Add code in appropriate places
        data() {
            return {
                items: ['keyboard', 'mouse', 'iPhone', 'macbook', 'adapter']
            }
            
        }
    }
</script>

<template>

    <h2>Shopping Cart</h2>
    <ul v-for ="item in items">
        <li>
            {{item}}
        </li>
    </ul>
    Student Name: <input type="text" v-model="studName"></input>
    <!-- TODO: Add Code Here -->
   
</template>
