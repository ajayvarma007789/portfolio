<style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        .animate-fadeIn {
            animation: fadeIn 2s ease-in-out forwards;
            animation-delay: 0.7s;
        }
</style>


<script lang=ts>
    import Textanimation from "../components/textanimation.svelte";    
</script>

<header class=" mt-8 text-white font-Montserrat flex justify-center items-center md:gap-[500px] gap-[300px]">
    <img src="/header.png" alt="logo" class="w-[60px]">
    <p class="text-2xl  hidden sm:block">Ajay Varma</p>
</header>

<section id="Home" class="flex justify-center items-center sm:h-screen h-[50vh] w-full">
    <img class="text-white sm:-mt-36 px-10 sm:w-[800px] animate-fadeIn  w-[400px]" src="/Group 14.svg" alt="i am a developer">
</section>
<section id="Home" class=" flex justify-center items-center h-[50vh] sm:h-screen w-full">
    <img class="text-white -mt-36 px-10 sm:w-[900px] w-[400px]" src="/Group 1.png" alt="i am a designer">
</section>
<section id="About" class="h-screen w-full">
    <div class="lg:text-5xl md:text-4xl text-2xl font-bold font-Montserrat flex flex-col justify-center items-center">
        <Textanimation text="FRONTEND DEVELOPER"/>
        <Textanimation text="AND"/>
        <Textanimation text="GRAPHICS DESIGNER"/>
    </div>
    <div class="lg:text-xl md:text-lg text-sm font-Montserrat  flex flex-col items-center m-5 mx-20 opacity-60">
        <Textanimation text="I am <em>AJAY VARMA<em/>, Self-taught Frontend Web Developer and Graphics Designer. Computer Science with Cyber Security Engineering Student at SJCET Palai"/>
    </div>

    <div class="text-2xl md:text-3xl lg:text-4xl font-Montserrat flex flex-col items-center mt-20 sm:mt-15">
        <em>
            <Textanimation text="Tools used so far"/>
        </em>
    </div>

    <div class="lg:text-xl md:text-lg text-sm font-Montserrat  flex flex-col items-center -mb-14 opacity-60">
        <Textanimation text="[Tools,Softwares and Libraries used]"/>
    </div>

    <div class="grid justify-items-center my-20 mx-40 gap-1 grid-cols-2 lg:grid-cols-8 md:grid-cols-4" >
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/vscode.svg" loading="lazy" alt="VS Code" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/css.svg" loading="lazy" alt="python" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/html.svg" loading="lazy" alt="c" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/bootstrap.svg" loading="lazy" alt="java" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/tailwindcss.svg" loading="lazy" alt="javascript" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/reactjs.svg" loading="lazy" alt="typescript" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/next.js.svg" loading="lazy" alt="godot" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/shadcn.svg" loading="lazy" alt="svelte" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/javascript.svg" loading="lazy" alt="react" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/typescript.svg" loading="lazy" alt="html" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/svelte.svg" loading="lazy" alt="css" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/vite.svg" loading="lazy" alt="bootstrap" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/git.svg" loading="lazy" alt="tailwind" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/figma.svg" loading="lazy" alt="mysql" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/python.svg" loading="lazy" alt="git" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/java.svg" loading="lazy" alt="github" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div class="flex group items-center backdrop-blur-md hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/photoshop.svg" loading="lazy" alt="figma" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        
        
    </div>
    
</section>
<section id="Projects" class="h-screen w-full">
    <img class="text-white" src="" alt="coolpic2">
    <!-- projectcards -->
    <p class="text-white">hello</p>

</section>
<section id="Contact" class="h-screen w-full">
    <a href="githublink"><img src="" alt="github"></a>
    <a href="instalink"><img src="" alt="github"></a>
    <a href="linkedin"><img src="" alt="github"></a>
    <a href="dribbble"><img src="" alt="github"></a>
    <a href="x"><img src="" alt="github"></a>
    <a href="whatsapp"><img src="" alt="github"></a>
    <p class="text-white">hello</p>


</section>
<section id="Skills" class="h-screen w-full">
    <!-- tools and frame works -->
    <p class="text-white">hello</p>

</section>
<section id="Footer">
    <p class="text-white">hello</p>

</section>