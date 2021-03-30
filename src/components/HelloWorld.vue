<template>
  <div class="w-11/12">
    <div class="flex justify-center pb-10">
            <img src="../assets/Sharif.jpeg" class="h-40 w-40 rounded-full object-cover content-center" alt="username"/>
            <div class="ml-10" id="div1">
                <div class="flex items-center">
                    <h2 class="block leading-relaxed font-light text-gray-700 text-3xl">Sharif</h2>
                    
                    <button class="flex items-center ml-3 border border-blue-600 hover:bg-blue-600 hover:text-white rounded outline-none focus:outline-none bg-transparent text-blue-600 text-sm py-1 px-2">
                        <span class="block">Certified</span>
                        <svg class="block h-5 w-5 pl-1" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                        </svg>
                    </button>
                    <a class="cursor-pointer ml-2 p-1 border-transparent text-gray-700 rounded-full hover:text-blue-600 focus:outline-none focus:text-gray-600"
                    aria-label="Notifications">
                        <svg class="h-8 w-8" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24">
                            <path d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"/>
                            <path d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                        </svg>
                    </a>
                </div>

                <ul class="flex justify-content-around items-center">
                    <li>
                        <span class="block text-base flex"><span class="font-bold mr-2">23 </span> Posts</span>
                    </li>
                    <li>
                        <span class="cursor-pointer block text-base flex ml-5"><span class="font-bold mr-2">102k </span> Followers</span>
                    </li>
                    <li>
                        <span class="cursor-pointer block text-base flex ml-5"><span class="font-bold mr-2">654 </span> followed</span>
                    </li>
                </ul>
                <br>
                <div class="text-center md:text-left">
                    <span class="text-base">I am Sharif, I like playing game, read books and watch anime.</span>
              </div>
            </div>
      </div>


    <div class="border-b border-gray-300"></div>
    <article class="mt-5 grid grid-cols-3 gap-10">
        <div class="cursor-pointer relative" style="width:300px; height:300px">
            <img src="https://i.redd.it/qlsz3xe1zft41.jpg"
                class="foto w-full h-full object-cover"
                alt="description" />
        </div>
        <div class="cursor-pointer relative" style="width:300px; height:300px">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRGjI695s72lPw5Kc60isdle3W0sIJ8rvO0x6n3KusXC-kU43pJBh5nLB6utYjc1B8sUWU&usqp=CAU"
                class="foto w-full h-full object-cover"
                alt="description" />
        </div>
        <div class="cursor-pointer relative" style="width:300px; height:300px">
            <img src="https://qph.fs.quoracdn.net/main-qimg-f683cfdf287c9a8f76a74ae63a2e8b82"
                class="foto w-full h-full object-cover"
                alt="description" />
        </div>
    </article>
  </div>  
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#div1 {
  position: flex;
}
</style>
