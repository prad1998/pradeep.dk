<script>
 
 export let y;
 let tabs = [   
    {name: 'Projects', link:"#projects"},
    {name: 'About me', link:"#about"},
    {name: 'Login', link:"#login"},

    //    {name: 'Blog', '#blog'}
]
 


</script>

<header class={'sticky z-[100] top-0 duration-200 px-6 flex items-center justify-between border-solid' + (
    y>0 ? 'py-4 bg-slate-950 border' : 'py-6 bg-transparent border-transparent'
)}>
<h1 class="font-medium">
    <b class="font-bold poppins">Pradeep</b> Thayaparan
</h1>
<div class="sm:flex items-center gap-4 hidden">

{#each tabs as tab,index}
   <a href={tab.link} class="duration-200 hover:text-violet-400">
    <p>{tab.name}</p>
   </a> 
{/each} 
</div>
<a href="https://linkedin.com/in/pradeepthayaparan-8488b6196" target="_blank"  class="blueShadow relative overflow-hidden px-5 py-2 group rounded-full bg-white text-slate-950 ">
<div class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200 ">

</div>
<h4 class="relative z-9 text-black">Get in Touch</h4>

</a>

</header>