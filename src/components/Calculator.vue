<!-- eslint-disable -->
<template>
  <div class="h-screen bg-green-400 flex justify-center py-16">    
    <div class="w-1/3">
      <div class="p-4 text-right shadow-2xl rounded-t-lg bg-white">
        <p class="font-semibold text-gray-700 h-6">{{ getOperation }}</p>
        <p class="font-bold text-3xl text-gray-900 my-2">{{ getResult }}</p>
      </div>

      <div class="grid grid-cols-4 grid-rows-5 shadow-2xl rounded-b-lg">
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 col-span-2 hover:bg-green-600">AC</button>
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">DEL</button>
        <button class="h-16 text-xl text-white font-semibold bg-gray-700 border-gray-600 hover:bg-gray-800">%</button>

        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">7</button>
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">8</button>
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">9</button>
        <button class="h-16 text-xl text-white font-semibold bg-gray-700 border-gray-600 hover:bg-gray-800">X</button>

        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">4</button>
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">5</button>
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">6</button>
        <button class="h-16 text-xl text-white font-semibold bg-gray-700 border-gray-600 hover:bg-gray-800">-</button>

        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">3</button>
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">2</button>
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">1</button>
        <button class="h-16 text-xl text-white font-semibold bg-gray-700 border-gray-600 hover:bg-gray-800">+</button>

        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 col-span-2 hover:bg-green-600">0</button>
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">.</button>
        <button class="h-16 text-xl text-white font-semibold bg-green-500 border-green-400 hover:bg-green-600">=</button>
      </div>
    </div>      
    
  </div>
</template>
  
  <script>
  export default {
    data(){
      return{
        getOperation:'',
        getResult:0
      }
    },
    methods:{

    }
  };
  </script>  