<script>
  import logo from "./assets/HALO WITHOUT THE BG SHADOW.svg"
  import link from "./assets/iconmonstr-link-thin.svg"
</script>
<div id="container" class=" w-screen h-screen flex">
  <div class=" m-auto w-fit block bg-opacity-40 mx-auto justify-center text-center text-white ">
    <div class=" w-fit p-10 m-auto rounded-lg bg-[#171719] mt-10 font-light bg-opacity-70 text-lg">
      <div class=" fadeinanim">
        <img src={logo} alt="logo" class=" imgrotate h-[300px]">
        <div class=" mt-10  ">
          <b>This website is under construction<br></b>
          <div class=" " >
            <button on:click={() => window.location.href = "https://linktr.ee/solsticemit"} class="w-fit h-fit p-2 bg-black m-auto rounded-md mt-5 opacity-50 focus:opacity-100 hover:opacity-100 duration-150 transition-all fill-white"><img src={link} class="h-[24px] w-[24px]" alt="link"></button>
          </div>
          
        </div>
      </div>

    </div>
  </div>
</div>