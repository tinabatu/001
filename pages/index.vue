<template>
 <div>



<div class="w-screen h-screen" id="fullscreen">
        <div class="absolute inset-0">
            <img class="object-cover w-full h-full" src="/Mask groupcopertina.png" alt="A computer background">
            <div class="mix-blend-multiply"></div>
          </div>
        <div class="relative" id="relative">
           <nav class="flex items-center w-full h-24 select-none" x-data="{ showMenu: false }">
            <div class="relative flex flex-wrap items-center justify-between w-full h-24 mx-auto font-medium md:justify-center">
                <a href="/index" class="w-1/4 py-4 pl-6 pr-4 md:pl-4 md:py-0">
               <img src="/Frame.png" class="mr-4 h-6 sm:h-9" alt="logo" />
                </a>
                <div class="fixed top-0 left-0 z-40 items-center hidden w-full h-full p-3 text-xl bg-gray-900 bg-opacity-50 md:text-sm lg:text-base md:w-3/4 md:bg-transparent md:p-0 md:relative md:flex" :class="{'flex': showMenu, 'hidden': !showMenu }">
                    <div class="flex-col w-full h-auto h-full overflow-hidden bg-white rounded-lg select-none md:bg-transparent md:rounded-none md:relative md:flex md:flex-row md:overflow-auto">
                        <div class="flex flex-col items-center justify-center w-full h-full mt-12 text-center text-indigo-700 md:text-indigo-200 md:w-2/3 md:mt-0 md:flex-row md:items-center">
                            <a href="#" class="inline-block px-4 py-2 mx-2 font-medium text-left text-indigo-700 md:text-white md:px-0 lg:mx-3 md:text-center">Home</a>
                            <a href="#" class="inline-block px-0 px-4 py-2 mx-2 font-medium text-left md:px-0 hover:text-indigo-800 md:hover:text-white lg:mx-3 md:text-center">I nostri chef</a>
                            <a href="/comefunziona" class="inline-block px-0 px-4 py-2 mx-2 font-medium text-left md:px-0 hover:text-indigo-800 md:hover:text-white lg:mx-3 md:text-center">Come funziona</a>
                            <a href="#" class="inline-block px-0 px-4 py-2 mx-2 font-medium text-left md:px-0 hover:text-indigo-800 md:hover:text-white lg:mx-3 md:text-center">Registrazione chef</a>
                        </div>
                        <div class="flex flex-col items-center justify-end w-full h-full pt-4 md:w-1/3 md:flex-row md:py-0">
                            <a href="#_" class="w-full pl-6 mr-0 text-indigo-200 hover:text-white md:pl-0 md:mr-3 lg:mr-5 md:w-auto">Sign In</a>
                            <a href="#_" class="inline-flex items-center justify-center px-4 py-2 mr-1 text-base font-medium leading-6 text-indigo-600 whitespace-no-wrap transition duration-150 ease-in-out bg-white border border-transparent rounded-full hover:bg-white focus:outline-none focus:border-indigo-700 focus:shadow-outline-indigo active:bg-indigo-700">Sign Up</a>
                        </div>
                    </div>
                </div>
                <div @click="showMenu = !showMenu" class="absolute right-0 z-50 flex flex-col items-end w-10 h-10 p-2 mr-4 rounded-full cursor-pointer md:hidden hover:bg-gray-900 hover:bg-opacity-10 text-gray-100" :class="{ 'text-gray-400': showMenu, 'text-gray-100': !showMenu }">
                    <svg class="w-6 h-6" x-show="!showMenu" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor">
                        <path d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                    <svg class="w-6 h-6" x-show="showMenu" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" style="display: none;">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                    </svg>
                </div>
            </div>
        </nav>
        
        <div class="container py-32 mx-auto text-center sm:px-4">

            <h1 class="text-4xl font-extrabold leading-10 tracking-tight text-white sm:text-5xl sm:leading-none md:text-6xl xl:text-7xl"><span class="block">AGGIUNGI UN POSTO A CASA:
</span> <span class="relative inline-block mt-3 text-transparent text-yellow-500">ARRIVA IL RISTORANTE!</span></h1>
            <div class="max-w-lg mx-auto mt-6 text-sm text-center text-white md:mt-12 sm:text-base md:max-w-xl md:text-lg xl:text-xl">
Prova il nuovo format di food delivery a casa scegliendo
il tuo preferito tra i più richiesti
Chef di Milano.</div>
            <div class="relative flex items-center max-w-md mx-auto mt-12 overflow-hidden text-center rounded-full">
   	<form class="m-4 flex">
    	<input class="rounded-l-lg p-4 border-t mr-0 border-b border-l text-gray-800 border-gray-200 bg-white" placeholder="email"/>
		<button class="px-8 rounded-r-lg bg-purple-900  text-white font-bold p-4 uppercase ">Prenota ora</button>
	</form>
            </div>
            
        </div>
          
                
            </div>
        </div>
   
   <div class="p-10"></div>
  
             <h1 class="text-2xl p-10 font-bold text-center tracking-tight text-purple-900 sm:text-5xl sm:leading-none"><span class="block">Sì, hai letto bene il nostro slogan:<br>
non sei tu che vai al ristorante,</span><span class="text-2xl p-10 font-bold text-center tracking-tight text-yellow-500 sm:text-5xl sm:leading-none">è il ristorante che arriva da te.</span></h1>


<div class="p-10"></div>

    <div class="box-border flex flex-col items-center content-center px-8 mx-auto leading-6 text-black border-0 border-gray-300 border-solid md:flex-row max-w-7xl lg:px-16">

        <!-- Image -->
        <div class="box-border relative w-full max-w-md px-4 mt-5 mb-4 -ml-5 text-center bg-no-repeat bg-contain border-solid md:ml-0 md:mt-0 md:max-w-none lg:mb-0 md:w-1/2 xl:pl-10">
            <img src="/Group 6.png" class="p-2 pl-6 pr-5 xl:pl-16 xl:pr-20 ">
        </div>

        <!-- Content -->
        <div class="box-border order-first w-full text-black border-solid md:w-1/2 md:pl-5 md:order-none">
          <img src="/CHEFLIVERY è infatti una nuova esperienza per gli amanti del food grazie a cui sperimentare menù di qualità e nuove tipologie di cucina restando serenamente a casa..png" class="p-2 pl-6 pr-5 xl:pl-16 xl:pr-20 ">
           
        </div>
    </div>

<div class="p-10"></div>

    <div class="box-border flex flex-col items-center content-center px-8 mx-auto leading-6 text-black border-0 border-gray-300 border-solid md:flex-row max-w-7xl lg:px-16">

        <!-- Image -->
        <div class="box-border relative w-full max-w-md px-4 mt-5 mb-4 -ml-5 text-center bg-no-repeat bg-contain border-solid md:ml-0 md:mt-0 md:max-w-none lg:mb-0 md:w-1/2 xl:pl-10">
            <img src="/Perchè abbiamo pensato a questa proposta_ Il cibo a domicilio, dato l’intervallo di tempo tra la preparazione e la consegna, non può fisiologicamente mantenere la stessa bontà di un pasto appena sfornato..png" class="p-2 pl-6 pr-5 xl:pl-16 xl:pr-20 ">
        </div>

        <!-- Content -->
         <div class="box-border relative w-full max-w-md px-4 mt-5 mb-4 -ml-5 text-center bg-no-repeat bg-contain border-solid md:ml-0 md:mt-0 md:max-w-none lg:mb-0 md:w-1/2 xl:pl-10">
            <img src="/Group 5.png" class="p-2 pl-6 pr-5 xl:pl-16 xl:pr-20 ">
           
        </div>
    </div>
 
 <div class="p-10"></div>

<div class="box-border flex flex-col items-center content-center px-8 mx-auto leading-6 text-black border-0 border-gray-300 border-solid md:flex-row max-w-7xl lg:px-16">

        <!-- Image -->
        <div class="box-border relative w-full max-w-md px-4 mt-5 mb-4 -ml-5 text-center bg-no-repeat bg-contain border-solid md:ml-0 md:mt-0 md:max-w-none lg:mb-0 md:w-1/2 xl:pl-10">
            <img src="/Group 4.png" class="p-2 pl-6 pr-5 xl:pl-16 xl:pr-20 ">
        </div>

        <!-- Content -->
        <div class="box-border order-first w-full text-black border-solid md:w-1/2 md:pl-5 md:order-none">
          <img src="/l ristorante è invece spesso causa di stress_ tavoli non disponibili, costi alti di servizio, sovraffollamento durante il week end, perdite di tempo e stanchezza a causa degli spostamenti in città..png" class="p-2 pl-6 pr-5 xl:pl-16 xl:pr-20 ">
           
        </div>
    </div>


<div class="p-10"></div>


<div class="w-screen h-75" id="fullscreen"> 

            <img class="object-cover w-full h-30" src="/Mask group.png" alt="A computer background">
 
</div>


<!-- icons -->
<section class="py-12 sm:py-16 bg-white">  <h1 class="p-12 text-2xl font-bold text-center tracking-tight text-purple-900 sm:text-5xl sm:leading-none"><span class="block">Leggi qui sotto tutti i vantaggi<br>
</span><span class="text-2xl font-bold text-center tracking-tight text-yellow-500 sm:text-5xl sm:leading-none">di provare questa nuova esperienza.</span></h1>
    <div class="max-w-7xl px-10 mx-auto sm:text-center">

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-10 my-12 sm:my-16">
            <div class="rounded-lg py-10 flex flex-col items-center justify-center">
                <img class="w-13 h-13" viewBox="0 0 256 256" src="/image 1.png">
                <p class="mt-2 text-xl text-sm text-black-500">Il miglior modo per
divertirsi in compagnia:
vivere una nuova
esperienza insieme.</p>
            </div>
             <div class="rounded-lg py-10 flex flex-col items-center justify-center">
                <img class="w-13 h-13" viewBox="0 0 256 256" src="/image 2.png">
                <p class="mt-2 text-xl text-black-500">Parteciperanno i migliori
Chef della città, ma sarai
proprio tu a scegliere 
il tuo preferito tra
le
tante proposte.</p>
            </div>
             <div class="rounded-lg py-10 flex flex-col items-center justify-center">
                <img class="w-13 h-13" viewBox="0 0 256 256" src="/image 3.png">
                <p class="mt-2 text-xl text-black-500">Compili il form di
richiesta.
Scegli lo Chef ed il Menù
che ti convince. Provi
una nuova
esperienza
culinaria.</p>
            </div>
  <div class="rounded-lg py-10 flex flex-col items-center justify-center">
                <img class="w-13 h-13" viewBox="0 0 256 256" src="/image 4.png">
                <p class="mt-2 text-xl text-black-500">Non solo proposte
di
Menù dei più grandi
Chef a domicilio.
Potrai proporre tu
gli ingredienti!</p>
            </div>
     <div class="rounded-lg py-10 flex flex-col items-center justify-center">
                <img class="w-13 h-13" viewBox="0 0 256 256" src="/image 5.png">
                <p class="mt-2 text-xl text-black-500">Scommettiamo
che non
hai mai accolto un
Ristorante a casa
tua.
Ma... ecco la prima
volta!</p>
            </div>
            <div class="rounded-lg py-10 flex flex-col items-center justify-center">
                <img class="w-13 h-13" viewBox="0 0 256 256" src="/image 6.png">
                <p class="mt-2 text-xl text-black-500">Tutti viviamo per
raccontare nuove
emozionanti avventure.
La prossima sarà
proprio questa?</p>
            </div>
            <div class="rounded-lg py-10 flex flex-col items-center justify-center">
                <img class="w-13 h-13" viewBox="0 0 256 256" src="/image 7.png">
                <p class="mt-2 text-xl text-black-500">Nessuno stress.
Nessuna
attesa. La bellezza
di stare
a casa combinata
con
le bontà dei piatti
di
un grande Chef.</p>
            </div>
            <div class="rounded-lg py-10 flex flex-col items-center justify-center">
                <img class="w-13 h-13" viewBox="0 0 256 256" src="/image 8.png">
                <p class="mt-2 text-xl text-black-500">Nessuno stress.
Nessuna
attesa. La bellezza
di stare
a casa combinata
con le bontà dei piatti
di un grande Chef.</p>
            </div>
           
        </div>

    </div>
</section>





   <div class="max-w-10 px-2 mx-8 sm:text-center">
     
     <h1 class="text-2xl font-bold text-center tracking-tight text-purple-900 sm:text-5xl sm:leading-none">Come funziona
<span class="text-2xl font-bold text-center tracking-tight text-yellow-500 sm:text-5xl sm:leading-none">Cheflivery?</span></h1>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-5 my-8 sm:my-16">
            <div class="rounded-lg py-2 flex flex-col items-center justify-center">
                <img class="w-auto h-auto" viewBox="0 0 256 256" src="/Group 15.png">
             </div>
             <div class="rounded-lg py-8 flex flex-col items-center justify-center">
                <img class="w-auto h-auto" viewBox="0 0 256 256" src="/Group 16.png">
                
            </div>
             <div class="rounded-lg py-8 flex flex-col items-center justify-center">
                <img class="w-auto h-auto" viewBox="0 0 256 256" src="/Group 17.png">
                
            </div>

           
        </div>

    </div>

<div class="p-10"></div>

<!-- cards -->
<section class="py-12 sm:py-15 bg-purple-50">  <h1 class="p-12 text-2xl font-bold text-center tracking-tight text-purple-900 sm:text-5xl sm:leading-none">Scegli
<span class="text-2xl font-bold text-center tracking-tight text-yellow-500 sm:text-5xl sm:leading-none">lo chef</span></h1>
    <div class="max-w-7xl px-10 mx-auto sm:text-center">

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-10 my-12 sm:my-16 items-center justify-center">
 
         <div class="relative pl-1 flex justify-center grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 rounded-xl hover:scale-105 duration-500 transform transition cursor-pointer rounded-lg py-10 flex flex-col items-center justify-center">

        <div class="w-80 h-50 pb-2 bg-white rounded-xl shadow-xl">
            <div class="relative">
            <!-- :src="image.largeImageURL"     -->
                <img src="/card1.png" class="max-h-70 object-cover rounded-t-xl" alt="card1">
                <!-- Tag rekomendasi -->
                <div class="bottom-6 left-2 w-20 h-8 px-3 rounded-lg absolute bg-yellow-500 text-white text-xs font-medium">50 euro a persona</div>
            </div>
            <div class="px-2 py-1">
                <!-- Product Title -->
                <div class="font-bold text-2xl pr-2">Chef nome</div>
                <div class="flex py-2">
                    <!-- Distance -->
                    <div class="bg-gray-200 p-1 mr-2 rounded-full text-xs font-regular text-gray-900">
                        0.5 Km
                    </div>
                    <div class="flex justify-between item-center">
                            <div class="flex items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                             
                            </div>
                    </div>
                </div>
                <!-- Alamat -->
                <p class="pb-1 md:pb-2 text-xs md:text-sm text-gray-500">Specializzato nella cucina mediterranea, disponibilità anche per piatti vegetariani e senza glutine.</p>
                <!-- Tombol pesan -->
                <a class="inset-x-center bottom-0 bg-yellow-500 hover:bg-purple-800 text-sm md:text-base border rounded-xl w-20 md:w-16 p-1 text-gray-100 hover:text-white" href="/inostrichef">Scopri lo chef...</a>
            </div>
        </div>


    </div> 
    

             <div class="relative pl-1 flex justify-center grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 rounded-xl hover:scale-105 duration-500 transform transition cursor-pointer rounded-lg py-10 flex flex-col items-center justify-center">

        <div class="w-80 h-50 pb-2 bg-white rounded-xl shadow-xl">
            <div class="relative">
            <!-- :src="image.largeImageURL"     -->
                <img src="/card1.png" class="max-h-70 object-cover rounded-t-xl" alt="card1">
                <!-- Tag rekomendasi -->
                <div class="bottom-6 left-2 w-20 h-8 px-3 rounded-lg absolute bg-yellow-500 text-white text-xs font-medium">50 euro a persona</div>
            </div>
            <div class="px-2 py-1">
                <!-- Product Title -->
                <div class="font-bold text-2xl pr-2">Chef nome</div>
                <div class="flex py-2">
                    <!-- Distance -->
                    <div class="bg-gray-200 p-1 mr-2 rounded-full text-xs font-regular text-gray-900">
                        0.5 Km
                    </div>
                    <div class="flex justify-between item-center">
                            <div class="flex items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                             
                            </div>
                    </div>
                </div>
                <!-- Alamat -->
                <p class="pb-1 md:pb-2 text-xs md:text-sm text-gray-500">Specializzato nella cucina mediterranea, disponibilità anche per piatti vegetariani e senza glutine.</p>
                <!-- Tombol pesan -->
                <a class="inset-x-center bottom-0 bg-yellow-500 hover:bg-purple-800 text-sm md:text-base border rounded-xl w-20 md:w-16 p-1 text-gray-100 hover:text-white" href="#">Scopri lo chef...</a>
            </div>
        </div>


    </div> 

             <div class="relative pl-1 flex justify-center grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 rounded-xl hover:scale-105 duration-500 transform transition cursor-pointer rounded-lg py-10 flex flex-col items-center justify-center">

        <div class="w-80 h-50 pb-2 bg-white rounded-xl shadow-xl">
            <div class="relative">
            <!-- :src="image.largeImageURL"     -->
                <img src="/card1.png" class="max-h-70 object-cover rounded-t-xl" alt="card1">
                <!-- Tag rekomendasi -->
                <div class="bottom-6 left-2 w-20 h-8 px-3 rounded-lg absolute bg-yellow-500 text-white text-xs font-medium">50 euro a persona</div>
            </div>
            <div class="px-2 py-1">
                <!-- Product Title -->
                <div class="font-bold text-2xl pr-2">Chef nome</div>
                <div class="flex py-2">
                    <!-- Distance -->
                    <div class="bg-gray-200 p-1 mr-2 rounded-full text-xs font-regular text-gray-900">
                        0.5 Km
                    </div>
                    <div class="flex justify-between item-center">
                            <div class="flex items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg> <svg xmlns="http://www.w3.org/2000/svg" class="h-3 md:h-5 md:w-5 text-yellow-500" viewBox="0 0 20 20"
                                    fill="currentColor">
                                    <path
                                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                             
                            </div>
                    </div>
                </div>
                <!-- Alamat -->
                <p class="pb-1 md:pb-2 text-xs md:text-sm text-gray-500">Specializzato nella cucina mediterranea, disponibilità anche per piatti vegetariani e senza glutine.</p>
                <!-- Tombol pesan -->
                <a class="inset-x-center bottom-0 bg-yellow-500 hover:bg-purple-800 text-sm md:text-base border rounded-xl w-20 md:w-16 p-1 text-gray-100 hover:text-white" href="#">Scopri lo chef...</a>
            </div>
        </div>


    </div> 


           
        </div>



    </div>
</section>

<div class="p-10"></div>

<div class="box-border flex flex-col items-center content-center px-8 mx-auto leading-6 text-black border-0 border-gray-300 border-solid md:flex-row max-w-7xl lg:px-16">

        <!-- Image -->
        <div class="box-border relative w-full max-w-md px-4 mt-5 mb-4 -ml-5 text-center bg-no-repeat bg-contain border-solid md:ml-0 md:mt-0 md:max-w-none lg:mb-0 md:w-1/2 xl:pl-10">
            <img src="/Group 18.png" class="p-2 pl-6 pr-5 xl:pl-16 xl:pr-20 ">
        </div>

        <!-- Content -->
        <div class="box-border order-first w-full text-black border-solid md:w-1/2 md:pl-5 md:order-none">
          <img src="/Group 19.png">
           
        </div>
    </div>

<div class="p-10"></div>

       <div class="max-w-5 px-2 mx-8 sm:text-center">
     
     <h1 class="text-2xl p-8 font-bold text-center tracking-tight text-purple-900 sm:text-5xl sm:leading-none"><span class="block">SCEGLI IL MENÙ PIÙ<br>
</span><span class="text-2xl font-bold text-center tracking-tight text-yellow-500 sm:text-5xl sm:leading-none">ADATTO ALLE TUE ABITUDINI</span></h1>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-5 my-8 sm:my-16">
            <div class="rounded-lg py-8 flex flex-col items-center justify-center">
                <img class="w-auto h-auto" viewBox="0 0 256 256" src="/Group 20.png">
             </div>
             <div class="rounded-lg py-8 flex flex-col items-center justify-center">
                <img class="w-auto h-auto" viewBox="0 0 256 256" src="/Group 21.png">
                
            </div>
             <div class="rounded-lg py-8 flex flex-col items-center justify-center">
                <img class="w-auto h-auto" viewBox="0 0 256 256" src="/Group 22.png">
                
            </div>

           
        </div>

    </div>

      <h1 class="p-12 text-2xl font-bold text-center tracking-tight text-purple-900 sm:text-5xl sm:leading-none">Cosa dicono
<span class="text-2xl font-bold text-center tracking-tight text-yellow-500 sm:text-5xl sm:leading-none">di noi</span></h1>









<footer class="bg-purple-900">
  <div class="max-w-screen-xl px-4 py-16 mx-auto sm:px-6 lg:px-8">
    <div class="grid grid-cols-1 gap-8 lg:grid-cols-3">
      <div>
      <img src="/Frame.png" class="mr-5 h-6 sm:h-9" alt="logo" />

        <div class="flex mt-8 space-x-6 text-white">
          <a class="hover:opacity-75" href target="_blank" rel="noreferrer">
            <span class="sr-only"> Facebook </span>
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
              <path fillRule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clipRule="evenodd" />
            </svg>
          </a>
          <a class="hover:opacity-75" href target="_blank" rel="noreferrer">
            <span class="sr-only"> Instagram </span>
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
              <path fillRule="evenodd" d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z" clipRule="evenodd" />
            </svg>
          </a>



        </div>
      </div>
      <div class="grid grid-cols-1 gap-8 lg:col-span-2 sm:grid-cols-2 lg:grid-cols-4">
        <div>
          <p class="font-medium text-white">
            Cheflivery
          </p>
          <nav class="flex flex-col mt-4 space-y-2 text-sm text-white">
            <a class="hover:opacity-75" href> Home </a>
            <a class="hover:opacity-75" href> I nostri chef </a>
            <a class="hover:opacity-75" href> Come funziona </a>
            <a class="hover:opacity-75" href> Registrazione chef </a>
          </nav>
        </div>
        <div>
          <p class="font-medium text-white">
            Come funziona
          </p>
          <nav class="flex flex-col mt-4 space-y-2 text-sm text-white">
            <a class="hover:opacity-75" href> Cookie policy </a>
            <a class="hover:opacity-75" href> Termini e condizioni </a>

          </nav>
        </div>
        <div>

          <p class="font-medium text-white">
            Luogo
          </p>
          <nav class="flex flex-col mt-4 space-y-2 text-sm text-white">
            <p>Cheflivery Rushnet Srl
-Via Vincenzo Monti 8 Milano - Italia P. IVA 11194740962</p>


          </nav>


        </div>

      </div>
    </div>
    <p class="mt-8 text-xs text-white">
      © 2022 Cheflivery
    </p>
  </div>
</footer>













</div>





</template>

<script>


</script>






