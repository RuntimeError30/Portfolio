<script>
  import Darain from '../Images/darain2.jpg';
  import { onMount } from 'svelte';

</script>
  <style>
    #custom-cursor {
      cursor: url('../Images/mouse.png'), auto;
    }

    #links{
      @media (max-width:1024px){
        rotate: -90deg;
        font-size: 2px;

        
      }
    }


    #texts{
      @media (max-width:1024px) {
        font-size: 30px;

        
      }
    }


    #photo{
      @media (max-width:1024) {
        width: 15rem;
        display: flex;
         
      }
    }

    #photodetails{
      @media (max-width:1024px) {
        
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
         
      }
    }
  </style>
  
  <section class="m-8 lg:m-16" id="custom-cursor">

    <nav class="flex justify-between w-full">
      <a href="" class="uppercase text-sm font-semibold">PROFILE</a>
      <a href="" class="uppercase text-sm font-semibold">Projects</a>
    </nav>
  
    <div class="w-full flex flex-col items-center lg:flex-row justify-center mt-10  space-y-5 ">
      <div>
        <h1 class="text-3xl font-semibold">darain__khan</h1>
        <h1 class="text-sm">//Software Engineer</h1>
  
        <h1 class="w-56 text-sm mt-8 lg:mt-20 tracking-wide">
          Located in Dhaka, Bangladesh. <br />
          Also Mohammad Darain Khan is a Graphics Designer, 3D Designer, and Video Editor
        </h1>
      </div>
  
      <div class="flex  items-center" id="photodetails">
        <img src={Darain} alt="" class="aspect-square object-cover w-full " id="photo">
  
        <div class="grid  rotate-90 border-b p-5 " id=links>
          <a href="" style="font-family: 'Prata', serif;"  id="texts" class="text-4xl hover:text-5xl transition-all duration-700 text-[#bdbdbd]">Web Development</a>
  
          <a href="" style="font-family: 'Prata', serif;" id="texts" class="text-4xl hover:text-5xl transition-all duration-700 text-[#bdbdbd]">Graphics Designs</a>
          <a href="" style="font-family: 'Prata', serif;" id="texts" class="text-4xl  hover:text-5xl transition-all duration-700 text-[#bdbdbd]">3D Designs</a>
        </div>
      </div>
    </div>
  </section>
  