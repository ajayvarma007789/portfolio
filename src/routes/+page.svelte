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
            animation: fadeIn 2.5s ease-in-out forwards;   
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
    <img class="text-white -mt-36 px-10 sm:w-[900px] w-[400px] animate-fadeIn" src="/Group 1.png" alt="i am a designer">
</section>
<section id="About" class=" mb-16 w-full">
    <div class="lg:text-5xl md:text-4xl text-2xl font-bold font-Montserrat flex flex-col justify-center items-center">
        <Textanimation text="FRONTEND DEVELOPER"/>
        <Textanimation text="AND"/>
        <Textanimation text="GRAPHICS DESIGNER"/>
    </div>
    <div class="lg:text-lg md:text-md text-sm font-Montserrat  flex flex-col items-center m-5 mx-20 opacity-60">
        <Textanimation text="I am <em>AJAY VARMA<em/>, Self-taught Frontend Web Developer and Graphics Designer. Computer Science with Cyber Security Engineering Student at SJCET Palai"/>
    </div>

    <div class="text-2xl md:text-3xl lg:text-4xl font-Montserrat flex flex-col items-center mt-20 sm:mt-15">
        <em>
            <Textanimation text="Tools i learned till now "/>
        </em>
    </div>

    <div class="lg:text-lg md:text-md text-sm font-Montserrat  flex flex-col items-center opacity-60">
        <Textanimation text="Tools,Softwares and Libraries used"/>
    </div>

    <div class="grid justify-items-center mt-20 mx-10 sm:mx-40 gap-1 grid-cols-2 lg:grid-cols-8 md:grid-cols-4 overflow-visible" >
        <div title="vscode" class="flex group items-center  hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/vscode.svg" loading="lazy" alt="VS Code" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="css" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/css.svg" loading="lazy" alt="python" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="html" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/html.svg" loading="lazy" alt="c" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="bootstrap" class="flex group items-center  hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/bootstrap.svg" loading="lazy" alt="java" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="tailwindcss" class="flex group items-center  hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/tailwindcss.svg" loading="lazy" alt="javascript" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="reactjs" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/reactjs.svg" loading="lazy" alt="typescript" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="nextjs" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/next.js.svg" loading="lazy" alt="godot" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="shadcn" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/shadcn.svg" loading="lazy" alt="svelte" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="javascript" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/javascript.svg" loading="lazy" alt="react" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="typescript" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/typescript.svg" loading="lazy" alt="html" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="svelte" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/svelte.svg" loading="lazy" alt="css" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="vite" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/vite.svg" loading="lazy" alt="bootstrap" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="git" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/git.svg" loading="lazy" alt="tailwind" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="figma" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/figma.svg" loading="lazy" alt="mysql" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="python" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/python.svg" loading="lazy" alt="git" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="java" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/java.svg" loading="lazy" alt="github" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="photoshop" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/photoshop.svg" loading="lazy" alt="photoshop" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="Docker" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/docker.svg" loading="lazy" alt="docker" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="Bash" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/bash.svg" loading="lazy" alt="Bash" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        <div title="Powershell" class="flex group items-center hover:bg-white/5 hover:backdrop-blur-lg w-full h-24 justify-center rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="/powershell.svg" loading="lazy" alt="Powershell" class="group-hover:w-12 w-10 opacity-90 transition-all duration-300">
        </div>
        
    </div>
    
    
        
    
</section>

<section id="Projects" class="w-full sm:mb-16 text-white">

    <div class="text-2xl md:text-3xl lg:text-5xl font-Montserrat font-bold flex flex-col items-center mb-32">
        <em>
            <Textanimation text="Projects"/>
        </em>
    </div>

    <div class="grid justify-items-center my-20 mx-10 sm:mx-40 gap-10 grid-cols-1 lg:grid-cols-4 md:grid-cols-2">
        <div title="project" class="flex items-center justify-center ">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/3.webp" alt="project">
        </div>
        
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/4.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300 " src="/projects/5.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/6.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px] hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/7.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px] hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/8.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/9.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/10.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/11.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/12.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/13.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/14.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center rounded-xl">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/15.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/16.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center ">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/17.webp" alt="project">
        </div>
        <div title="project" class="flex items-center justify-center">
            <img class="w-[300px]  hover:w-[350px] rounded-xl border border-transparent hover:border-gray-700 transition-all duration-300" src="/projects/2.webp" alt="project">
        </div>

    </div>

   
</section>

<section id="contact">
    <div class="flex gap-5 -mt-12 mb-10 justify-center items-center  ">
        <a href="mailto:ajaydesigns75@gmail.com">
        <div class="flex hover:bg-white/5 hover:backdrop-blur-lg justify-center items-center p-5 text-white rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img src="email-30.png" alt="Email"> 
        </div>
        </a>
        
        <div class="flex gap-5 hover:bg-white/5 hover:backdrop-blur-lg justify-center items-center p-5 text-white rounded-md border border-transparent hover:border-gray-700 transition-all duration-300">
            <img class="w-[30px]" src="phone.png" alt="Phone"> 
            <p>
                +919530204516
            </p>
        </div>
    </div>

<div id="contact" class="grid gap-10 mb-10 mx-20 sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-4 justify-center items-center">
    <a href="https://github.com/ajayvarma007789">
        <div id="github" class="flex text-white p-5 gap-10 items-center hover:bg-white/10 hover:backdrop-blur-lg justify-center rounded-xl border  border-gray-700 transition-all duration-300">
            <img src="/github.svg" alt="github" class="w-16">
            <div class="">
                <p class="font-Montserrat lg:text-lg sm:text-md">Github</p>
                <em><p class="font-Montserrat lg:text-md sm:text-sm opacity-70">look here for more of my projects</p></em>
            </div>
        </div>
    </a>
    <a href="https://www.instagram.com/ajaydesigns2023?igsh=MWdrZ2pwNm4yMzl5dQ==">
        <div id="github" class="flex text-white p-5 gap-10 items-center hover:bg-white/10 hover:backdrop-blur-lg justify-center rounded-xl border  border-gray-700 transition-all duration-300">
            <img src="/instagram.svg" alt="instagram" class="w-14">
            <div >
                <p class="font-Montserrat lg:text-lg sm:text-md">Instagram</p>
                <em><p class="font-Montserrat lg:text-md sm:text-sm opacity-70">contact me through instagram</p></em>
            </div>
        </div>
    </a><a href="https://www.linkedin.com/in/ajay-varma-aaa71933b/">
        <div id="github" class="flex text-white p-5 gap-10 items-center hover:bg-white/10 hover:backdrop-blur-lg justify-center rounded-xl border  border-gray-700 transition-all duration-300">
            <img src="/linkedin.svg" alt="linkedin" class="w-14">
            <div >
                <p class="font-Montserrat lg:text-lg sm:text-md">Linkedin</p>
                <em><p class="font-Montserrat lg:text-md sm:text-sm opacity-70">contact me though linkedin</p></em>
            </div>
        </div>
    </a>
    <a href="https://x.com/AJAYVARMA123629">
        <div id="github" class="flex text-white p-5 gap-10 items-center hover:bg-white/10 hover:backdrop-blur-lg justify-center rounded-xl border  border-gray-700 transition-all duration-300">
            <img src="/twitter.svg" alt="x" class="w-14">
            <div >
                <p class="font-Montserrat lg:text-lg sm:text-md">Twitter</p>
                <em><p class="font-Montserrat lg:text-md sm:text-sm opacity-70">contact me through twitter</p></em>
            </div>
        </div>
    </a>
    
    <a href="https://dribbble.com/AjayVarmadesignare">
        <div id="dribbble" class="flex text-white p-5 gap-10 items-center hover:bg-white/10 hover:backdrop-blur-lg justify-center rounded-xl border  border-gray-700 transition-all duration-300">
            <img src="/dribbble.svg" alt="dribbble" class="w-14">
            <div >
                <p class="font-Montserrat lg:text-lg sm:text-md">Dribbble</p>
                <em><p class="font-Montserrat lg:text-md sm:text-sm opacity-70">Look at my designs in dribbble</p></em>
            </div>
        </div>
    </a>
</div>

</section>


