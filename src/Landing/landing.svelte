<script>
    import Darain from '../Images/darain2.jpg';
    import mouse from '../Images/mouse.png';
</script>

<style>
    #custom-cursor {
      cursor: url('../Images/mouse.png'),auto;
    }
  </style>

<section class=" m-16" id="custom-cursor">


    <nav class="flex justify-between w-full">
        <a href="" class="uppercase text-sm font-semibold">PROFILE</a>
        <a href="" class="uppercase text-sm font-semibold">PRojects</a>
    </nav>



    <div class="w-full flex justify-center">
        <div class="flex items-center mt-10 space-x-5">
            <!-- <img src={Darain} alt="" class="aspect-square object-cover w-72 rounded-full"> -->
    
            <div>
                <h1 class="text-3xl font-semibold ">darain__khan</h1>
                <h1 class="text-sm">//Software Engineer</h1>
    
                <h1 class="w-56 text-sm mt-20 tracking-wide">Located in Dhaka, Bangladesh. <br>  Also Mohammad Darain Khan is a 
                Graphics Designer, 3D Designer and Video Editor</h1>
            </div>
    

            <div class="flex items-center">
                <img src={Darain} alt="" class="aspect-square object-cover w-[40rem]">

                <div style="" class="grid rotate-90  border-b p-5">
                    <a href="" style="font-family: 'Prata', serif;" class="text-6xl hover:text-7xl transition-all duration-700 text-[#bdbdbd]">Web Development</a>

                    
                    <a href="" style="font-family: 'Prata', serif;" class="text-6xl hover:text-7xl transition-all duration-700 text-[#bdbdbd]">Graphics Designs</a>
                    <a href="" style="font-family: 'Prata', serif;" class="text-6xl hover:text-7xl transition-all duration-700 text-[#bdbdbd]">3D Designs</a>

                </div>
            </div>
    
            
        </div>
    </div>
</section>