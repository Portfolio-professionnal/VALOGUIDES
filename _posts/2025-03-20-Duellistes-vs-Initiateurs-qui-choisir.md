---
layout: post
title: "Duellistes vs. Initiateurs: Qui Choisir?"
date: 2025-04-20 10:00:00 +0100
category: Agents & Méta
excerpt: "Analyse détaillée des forces et faiblesses de chaque rôle et comment choisir selon la carte et la composition d'équipe."
image: "https://i.postimg.cc/5Np9654S/Design-sans-titre-1.webp"
---
<main class="pt-24 pb-16 bg-[#0F1923] text-white font-serif">
  <div class="container mx-auto px-4 max-w-4xl">
    <!-- Image en haut de l'article avec overlay et effet parallaxe -->
    <div class="mb-10 rounded-xl overflow-hidden shadow-2xl relative group">
      <div class="absolute inset-0 bg-gradient-to-t from-[#0F1923] via-transparent to-transparent z-10"></div>
      <img 
        src="{{ page.image }}"
        alt="{{ page.title }}" 
        loading="lazy"
        class="w-full h-96 object-cover object-center transition-transform duration-700 ease-in-out group-hover:scale-105"
      />
      <div class="absolute bottom-4 right-4 z-20">
        <span class="px-3 py-1 bg-[#FF4655] text-white rounded-full text-xs font-bold animate-pulse">META ANALYSE</span>
      </div>
    </div>
    
    <article class="prose prose-invert max-w-none">
      <!-- Titre et métadonnées avec badges et temps de lecture -->
      <div class="flex flex-col md:flex-row md:items-center justify-between mb-8 border-b border-gray-800 pb-4">
        <div>
          <h1 class="text-5xl font-bold mb-2 text-[#FF4655] leading-tight">{{ page.title }}</h1>
          <div class="flex items-center flex-wrap gap-2">
            <span class="text-gray-400 italic">20 avril 2025</span>
            <span class="text-gray-600">•</span>
            <span class="px-2 py-1 bg-[#1A242D] rounded-md text-[#FF4655] text-sm">{{ page.category }}</span>
            <span class="text-gray-600">•</span>
            <span class="text-gray-400">Temps de lecture: 12 min</span>
          </div>
        </div>
        <div class="mt-4 md:mt-0">
          <div class="flex items-center gap-2">
            <button class="px-3 py-1 bg-[#1A242D] hover:bg-[#FF4655] text-white rounded-md transition-colors flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-1"><path d="M7 10v12l10-6-10-6z"></path></svg>
              Partager
            </button>
            <button class="px-3 py-1 bg-[#1A242D] hover:bg-[#FF4655] text-white rounded-md transition-colors flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-1"><path d="M17 3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h10z"></path></svg>
              Imprimer
            </button>
          </div>
        </div>
      </div>
      
      <!-- Introduction avec animation et style amélioré -->
      <div class="bg-gradient-to-r from-[#1A242D] to-[#0F1923] rounded-lg p-6 mb-10 shadow-inner transform hover:-translate-y-1 transition-transform duration-300">
        <p class="text-xl text-gray-300 leading-relaxed">
          "Je prends Jett" — "Je lock Reyna" — "Prenez un initiateur svp". Ces phrases résonnent dans chaque lobby de Valorant depuis le lancement du jeu. La bataille éternelle entre Duellistes et Initiateurs continue en 2025, avec les uns accusant les autres de "bait" et les autres reprochant aux premiers leur manque d'utilité. Mais si on mettait de côté ces querelles de playground pour analyser objectivement : qui devriez-vous vraiment choisir ? Un rôle est-il supérieur à l'autre ? Et plus important encore, lequel maximisera vos chances de sortir enfin de ce maudit Platinum où vous stagnez depuis 16 actes ?
        </p>
      </div>
      
      <!-- Sommaire avec accordéon et animations -->
      <div class="mb-12 bg-[#1A242D] rounded-lg overflow-hidden shadow-md">
        <h2 class="text-2xl font-bold p-4 bg-[#FF4655] text-white flex items-center">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M4 6h16M4 12h16M4 18h7"></path></svg>
          Sommaire
        </h2>
        <div class="p-4 grid grid-cols-1 md:grid-cols-2 gap-4">
          <div class="col-span-1 md:col-span-2">
            <a href="#definition-roles" class="flex items-center p-3 bg-[#0F1923] rounded-md hover:bg-[#FF4655] transition-colors group">
              <span class="w-8 h-8 flex items-center justify-center rounded-full bg-[#FF4655] group-hover:bg-white text-white group-hover:text-[#FF4655] font-bold mr-2 transition-colors">1</span>
              <span class="font-medium">Définition des rôles</span>
            </a>
          </div>
          <a href="#duellistes-analyse" class="p-3 bg-[#0F1923] rounded-md hover:bg-[#FF4655] transition-colors">
            <span class="font-medium">Analyse des Duellistes</span>
          </a>
          <a href="#initiateurs-analyse" class="p-3 bg-[#0F1923] rounded-md hover:bg-[#FF4655] transition-colors">
            <span class="font-medium">Analyse des Initiateurs</span>
          </a>
          <a href="#comparaison-statistique" class="p-3 bg-[#0F1923] rounded-md hover:bg-[#FF4655] transition-colors">
            <span class="font-medium">Comparaison statistique</span>
          </a>
          <a href="#carte-comp" class="p-3 bg-[#0F1923] rounded-md hover:bg-[#FF4655] transition-colors">
            <span class="font-medium">Choix selon carte et composition</span>
          </a>
          <a href="#meta-actuelle" class="p-3 bg-[#0F1923] rounded-md hover:bg-[#FF4655] transition-colors">
            <span class="font-medium">Méta actuelle (2025)</span>
          </a>
          <a href="#conclusion" class="p-3 bg-[#0F1923] rounded-md hover:bg-[#FF4655] transition-colors">
            <span class="font-medium">Conclusion et recommandations</span>
          </a>
        </div>
      </div>
      
      <!-- Définition des rôles -->
      <div id="definition-roles" class="scroll-mt-24">
        <div class="flex items-center mb-6">
          <div class="w-12 h-12 rounded-full bg-[#FF4655] flex items-center justify-center mr-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path><polyline points="22 4 12 14.01 9 11.01"></polyline></svg>
          </div>
          <h2 class="text-3xl font-bold text-[#FF4655]">Définition des rôles</h2>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-12">
          <div class="bg-gradient-to-br from-[#1A242D] to-[#131C24] p-5 rounded-lg shadow-md transform hover:scale-105 transition-transform border-l-4 border-[#FF4655]">
            <h3 class="text-xl font-bold text-white mb-4 flex items-center">
              <img src="https://i.postimg.cc/C5F3jL1M/duellist-icon.webp" alt="Duelliste" class="w-8 h-8 mr-2">
              Les Duellistes
            </h3>
            <p class="text-gray-300 mb-4">
              Les duellistes sont conçus pour être les premiers à engager le combat et à créer de l'espace pour leur équipe. Leur kit se concentre sur la mobilité, les entrées agressives et l'élimination rapide des adversaires.
            </p>
            <div class="bg-[#0F1923] p-3 rounded-lg mb-4">
              <h4 class="font-medium mb-2 text-[#FF4655]">Caractéristiques principales:</h4>
              <ul class="space-y-2 text-gray-300 text-sm">
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>Mobilité et capacités d'entrée</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>Outils de repositionnement et d'échappement</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>Capacités favorisant les éliminations</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>Auto-suffisance relative</span>
                </li>
              </ul>
            </div>
            <div class="bg-[#0F1923] p-3 rounded-lg">
              <h4 class="font-medium mb-2 text-[#FF4655]">Agents représentatifs:</h4>
              <div class="flex flex-wrap gap-2">
                <span class="px-2 py-1 bg-[#FF4655] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/jett-icon.webp" alt="Jett" class="w-4 h-4 mr-1"> Jett
                </span>
                <span class="px-2 py-1 bg-[#FF4655] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/reyna-icon.webp" alt="Reyna" class="w-4 h-4 mr-1"> Reyna
                </span>
                <span class="px-2 py-1 bg-[#FF4655] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/raze-icon.webp" alt="Raze" class="w-4 h-4 mr-1"> Raze
                </span>
                <span class="px-2 py-1 bg-[#FF4655] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/phoenix-icon.webp" alt="Phoenix" class="w-4 h-4 mr-1"> Phoenix
                </span>
                <span class="px-2 py-1 bg-[#FF4655] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/neon-icon.webp" alt="Neon" class="w-4 h-4 mr-1"> Neon
                </span>
                <span class="px-2 py-1 bg-[#FF4655] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/yoru-icon.webp" alt="Yoru" class="w-4 h-4 mr-1"> Yoru
                </span>
              </div>
            </div>
          </div>
          
          <div class="bg-gradient-to-br from-[#1A242D] to-[#131C24] p-5 rounded-lg shadow-md transform hover:scale-105 transition-transform border-l-4 border-[#3498db]">
            <h3 class="text-xl font-bold text-white mb-4 flex items-center">
              <img src="https://i.postimg.cc/C5F3jL1M/initiator-icon.webp" alt="Initiateur" class="w-8 h-8 mr-2">
              Les Initiateurs
            </h3>
            <p class="text-gray-300 mb-4">
              Les initiateurs sont les experts en collecte d'informations et en préparation d'attaques. Ils combinent utilité offensive et capacités de reconnaissance pour dévoiler les positions ennemies et créer des opportunités.
            </p>
            <div class="bg-[#0F1923] p-3 rounded-lg mb-4">
              <h4 class="font-medium mb-2 text-[#3498db]">Caractéristiques principales:</h4>
              <ul class="space-y-2 text-gray-300 text-sm">
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>Capacités de reconnaissance et d'information</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>Utility pour neutraliser les défenses adverses</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>Support offensif pour l'équipe</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>Contrôle et déni de zones</span>
                </li>
              </ul>
            </div>
            <div class="bg-[#0F1923] p-3 rounded-lg">
              <h4 class="font-medium mb-2 text-[#3498db]">Agents représentatifs:</h4>
              <div class="flex flex-wrap gap-2">
                <span class="px-2 py-1 bg-[#3498db] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/sova-icon.webp" alt="Sova" class="w-4 h-4 mr-1"> Sova
                </span>
                <span class="px-2 py-1 bg-[#3498db] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/breach-icon.webp" alt="Breach" class="w-4 h-4 mr-1"> Breach
                </span>
                <span class="px-2 py-1 bg-[#3498db] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/skye-icon.webp" alt="Skye" class="w-4 h-4 mr-1"> Skye
                </span>
                <span class="px-2 py-1 bg-[#3498db] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/kayo-icon.webp" alt="KAY/O" class="w-4 h-4 mr-1"> KAY/O
                </span>
                <span class="px-2 py-1 bg-[#3498db] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/fade-icon.webp" alt="Fade" class="w-4 h-4 mr-1"> Fade
                </span>
                <span class="px-2 py-1 bg-[#3498db] bg-opacity-20 text-white rounded text-sm flex items-center">
                  <img src="https://i.postimg.cc/C5F3jL1M/gekko-icon.webp" alt="Gekko" class="w-4 h-4 mr-1"> Gekko
                </span>
              </div>
            </div>
          </div>
        </div>
        
        <div class="bg-[#1A242D] p-5 rounded-lg mb-12 border-t-4 border-[#FF4655]">
          <h4 class="font-bold mb-2 text-[#FF4655]">La différence fondamentale:</h4>
          <p class="text-gray-300">En simplifiant à l'extrême, les Duellistes sont conçus pour les joueurs qui veulent être les stars de la partie, prendre des duels et faire le spectacle, tandis que les Initiateurs sont pour ceux qui préfèrent jouer intelligemment, supporter l'équipe tout en ayant un impact significatif sur le résultat. Un duelliste crée l'espace, un initiateur permet à l'équipe d'utiliser cet espace efficacement.</p>
        </div>
      </div>
      
      <!-- Analyse des Duellistes -->
      <div id="duellistes-analyse" class="scroll-mt-24 mb-16">
        <div class="flex items-center mb-6">
          <div class="w-12 h-12 rounded-full bg-[#FF4655] flex items-center justify-center mr-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M12 19l9 2-9-18-9 18 9-2z"></path></svg>
          </div>
          <h2 class="text-3xl font-bold text-[#FF4655]">Analyse des Duellistes</h2>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
          <div class="bg-[#1A242D] rounded-lg overflow-hidden shadow-md col-span-1 md:col-span-2">
            <div class="bg-[#FF4655] bg-opacity-20 p-4">
              <h3 class="text-xl font-bold text-[#FF4655]">Forces</h3>
            </div>
            <div class="p-4">
              <ul class="space-y-3 text-gray-300">
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#FF4655] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Potentiel de frags élevé</strong>
                    <p class="text-sm">Kits optimisés pour obtenir des éliminations et faire la différence lors des gunfights.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#FF4655] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Mobilité et capacités de repositionnement</strong>
                    <p class="text-sm">Possibilité de prendre des angles inattendus et de se désengager après avoir créé l'espace.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#FF4655] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Autonomie</strong>
                    <p class="text-sm">Moins dépendants de l'équipe pour être efficaces, idéal en soloQ à bas/moyen ELO.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#FF4655] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Forte présence en early game</strong>
                    <p class="text-sm">Capacité à prendre rapidement le contrôle d'une zone et à mettre la pression dès le début du round.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#FF4655] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Capacité à porter une équipe</strong>
                    <p class="text-sm">Un duelliste en forme peut compenser les lacunes de ses coéquipiers par ses performances individuelles.</p>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          
          <div class="bg-[#1A242D] rounded-lg overflow-hidden shadow-md">
            <div class="bg-red-500 bg-opacity-20 p-4">
              <h3 class="text-xl font-bold text-red-400">Faiblesses</h3>
            </div>
            <div class="p-4">
              <ul class="space-y-3 text-gray-300">
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Utilité limitée pour l'équipe</strong>
                    <p class="text-sm">Peu de capacités bénéficiant directement aux coéquipiers.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Dépendance au skill mécanique</strong>
                    <p class="text-sm">Efficacité fortement liée aux capacités de visée et réflexes du joueur.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Vulnérabilité en late game</strong>
                    <p class="text-sm">Moins d'impact une fois l'utilité consommée, surtout en post-plant/retake.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Prévisibilité</strong>
                    <p class="text-sm">Patterns d'attaque souvent anticipés par des adversaires expérimentés.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Saturation dans les compos</strong>
                    <p class="text-sm">Trop de duellistes dans une équipe crée un déséquilibre d'utilité.</p>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
          <div class="bg-[#1A242D] p-5 rounded-lg">
            <h3 class="text-xl font-bold mb-4 text-[#FF4655] flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
              Profil de joueur idéal
            </h3>
            <ul class="space-y-2 text-gray-300">
              <li class="flex items-baseline">
                <span class="text-[#FF4655] mr-2">•</span>
                <span>Joueurs agressifs avec un fort skill mécanique</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#FF4655] mr-2">•</span>
                <span>Ceux qui préfèrent les entrées et first bloods</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#FF4655] mr-2">•</span>
                <span>Joueurs confiants dans leurs gunfights</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#FF4655] mr-2">•</span>
                <span>Ceux qui aiment jouer indépendamment</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#FF4655] mr-2">•</span>
                <span>Joueurs recherchant des highlights et moments spectaculaires</span>
              </li>
            </ul>
          </div>
          
<div class="bg-[#1A242D] p-5 rounded-lg">
            <h3 class="text-xl font-bold mb-4 text-[#FF4655] flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M12 2.69l5.66 5.66a8 8 0 1 1-11.31 0z"></path></svg>
              Meta duellistes 2025
            </h3>
            <p class="text-gray-300 mb-3">En 2025, après de nombreux ajustements, certains duellistes dominent clairement la méta :</p>
            <div class="space-y-3">
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/jett-icon.webp" alt="Jett" class="w-10 h-10 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Jett</h4>
                  <p class="text-sm text-gray-400">Toujours reine du méta malgré les 27 nerfs consécutifs. Sa mobilité reste inégalée et son dash fait toujours pleurer les développeurs.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#FF4655] bg-opacity-20 text-[#FF4655] px-2 py-0.5 rounded">S+ Tier</span>
                  </div>
                </div>
              </div>
              
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/raze-icon.webp" alt="Raze" class="w-10 h-10 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Raze</h4>
                  <p class="text-sm text-gray-400">L'explosive brésilienne reste redoutable sur les cartes à espaces restreints. Son ultime est la définition même du "skill button".</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#FF4655] bg-opacity-20 text-[#FF4655] px-2 py-0.5 rounded">A Tier</span>
                  </div>
                </div>
              </div>
              
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/reyna-icon.webp" alt="Reyna" class="w-10 h-10 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Reyna</h4>
                  <p class="text-sm text-gray-400">La snowball queen de Valorant. On l'adore quand elle est dans notre équipe, on la déteste en face. Reine du smurf incontestée.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#FF4655] bg-opacity-20 text-[#FF4655] px-2 py-0.5 rounded">A Tier</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <div class="bg-[#1A242D] p-5 rounded-lg mb-8 border-t-4 border-[#FF4655]">
          <h4 class="font-bold mb-2 text-[#FF4655]">L'état d'esprit du Duelliste:</h4>
          <p class="text-gray-300">Qu'on se le dise, choisir un duelliste, c'est signer un contrat tacite avec votre équipe : vous vous engagez à ne pas camper dans un coin, à prendre des risques calculés, et à être le premier à entrer sur site. Vous êtes là pour attirer l'attention et créer l'espace, pas pour bait vos teammates et farm les derniers kills. Le duelliste moyen pense que tout le monde est là pour le servir - un vrai duelliste sait qu'il est là pour servir son équipe... en faisant des frags spectaculaires, bien sûr.</p>
          <p class="text-gray-300 mt-3 italic">"Si je ne rush pas, qui le fera?" - Un duelliste, probablement</p>
        </div>
      </div>
      
      <!-- Analyse des Initiateurs -->
      <div id="initiateurs-analyse" class="scroll-mt-24 mb-16">
        <div class="flex items-center mb-6">
          <div class="w-12 h-12 rounded-full bg-[#3498db] flex items-center justify-center mr-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M22 12h-4l-3 9L9 3l-3 9H2"></path></svg>
          </div>
          <h2 class="text-3xl font-bold text-[#3498db]">Analyse des Initiateurs</h2>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
          <div class="bg-[#1A242D] rounded-lg overflow-hidden shadow-md col-span-1 md:col-span-2">
            <div class="bg-[#3498db] bg-opacity-20 p-4">
              <h3 class="text-xl font-bold text-[#3498db]">Forces</h3>
            </div>
            <div class="p-4">
              <ul class="space-y-3 text-gray-300">
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#3498db] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Information cruciale</strong>
                    <p class="text-sm">Capacité inégalée à révéler les positions ennemies et à informer l'équipe.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#3498db] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Utilité offensive puissante</strong>
                    <p class="text-sm">Flashes, stuns et autres capacités qui créent des ouvertures pour toute l'équipe.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#3498db] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Polyvalence</strong>
                    <p class="text-sm">Efficaces tant en attaque qu'en défense, en entrée qu'en support.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#3498db] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Impact en late game</strong>
                    <p class="text-sm">Retakes et post-plants facilités par les capacités de reconnaissance et de clearing.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#3498db] mr-2 mt-1"><polyline points="20 6 9 17 4 12"></polyline></svg>
                  <div>
                    <strong class="text-white">Adaptabilité tactique</strong>
                    <p class="text-sm">Permettent une prise de décision éclairée et des adaptations stratégiques mid-round.</p>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          
          <div class="bg-[#1A242D] rounded-lg overflow-hidden shadow-md">
            <div class="bg-red-500 bg-opacity-20 p-4">
              <h3 class="text-xl font-bold text-red-400">Faiblesses</h3>
            </div>
            <div class="p-4">
              <ul class="space-y-3 text-gray-300">
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Dépendance à l'équipe</strong>
                    <p class="text-sm">Efficacité réduite sans coéquipiers suivant les informations fournies.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Courbe d'apprentissage</strong>
                    <p class="text-sm">Nécessite une bonne connaissance des lineups et timings spécifiques.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Mobilité limitée</strong>
                    <p class="text-sm">Moins d'options de repositionnement rapide par rapport aux duellistes.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Vulnérabilité en entrée</strong>
                    <p class="text-sm">Moins adaptés pour être les premiers à entrer sans support.</p>
                  </div>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-red-400 mr-2 mt-1"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
                  <div>
                    <strong class="text-white">Ressources limitées</strong>
                    <p class="text-sm">Utilité souvent consommable et non renouvelable pendant le round.</p>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
          <div class="bg-[#1A242D] p-5 rounded-lg">
            <h3 class="text-xl font-bold mb-4 text-[#3498db] flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
              Profil de joueur idéal
            </h3>
            <ul class="space-y-2 text-gray-300">
              <li class="flex items-baseline">
                <span class="text-[#3498db] mr-2">•</span>
                <span>Joueurs au style réfléchi et méthodique</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#3498db] mr-2">•</span>
                <span>Ceux qui privilégient l'impact d'équipe aux actions solo</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#3498db] mr-2">•</span>
                <span>Joueurs avec une bonne communication</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#3498db] mr-2">•</span>
                <span>Stratèges qui aiment contrôler le rythme du jeu</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#3498db] mr-2">•</span>
                <span>Ceux qui excellent dans les situations de clutch et late-game</span>
              </li>
            </ul>
          </div>
          
          <div class="bg-[#1A242D] p-5 rounded-lg">
            <h3 class="text-xl font-bold mb-4 text-[#3498db] flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M12 2.69l5.66 5.66a8 8 0 1 1-11.31 0z"></path></svg>
              Meta initiateurs 2025
            </h3>
            <p class="text-gray-300 mb-3">L'évolution de la méta a finalement donné aux initiateurs une place de choix :</p>
            <div class="space-y-3">
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/sova-icon.webp" alt="Sova" class="w-10 h-10 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Sova</h4>
                  <p class="text-sm text-gray-400">L'archétype de l'initiateur. Ses flèches de reconnaissance sont comme les impôts - inévitables et personne n'y échappe.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#3498db] bg-opacity-20 text-[#3498db] px-2 py-0.5 rounded">S Tier</span>
                  </div>
                </div>
              </div>
              
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/fade-icon.webp" alt="Fade" class="w-10 h-10 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Fade</h4>
                  <p class="text-sm text-gray-400">La reine du cauchemar. Jouer contre une bonne Fade, c'est comme être hanté par ses propres peurs - on ne peut jamais se cacher.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#3498db] bg-opacity-20 text-[#3498db] px-2 py-0.5 rounded">S Tier</span>
                  </div>
                </div>
              </div>
              
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/skye-icon.webp" alt="Skye" class="w-10 h-10 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Skye</h4>
                  <p class="text-sm text-gray-400">L'australienne qui transforme les oiseaux en outils de guerre. Sa flash informative reste l'une des plus frustrantes du jeu.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#3498db] bg-opacity-20 text-[#3498db] px-2 py-0.5 rounded">A+ Tier</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <div class="bg-[#1A242D] p-5 rounded-lg mb-8 border-t-4 border-[#3498db]">
          <h4 class="font-bold mb-2 text-[#3498db]">L'état d'esprit de l'Initiateur:</h4>
          <p class="text-gray-300">Être initiateur, c'est accepter que vos statistiques ne reflèteront jamais votre véritable impact. C'est flasher parfaitement pour que votre Reyna fasse un triple kill et recevoir un "Nice flash" au lieu d'un "Merci". C'est scanner intelligemment pour permettre un retake parfait et voir votre duelliste poster le clip sur TikTok sans même vous mentionner. Mais vous savez au fond de vous que sans vous, cette équipe ne serait qu'une bande de poulets sans tête courant vers leur mort.</p>
          <p class="text-gray-300 mt-3 italic">"Je flashe, tu tues" - Le mantra de tous les initiateurs depuis 2020</p>
        </div>
      </div>
      
      <!-- Comparaison statistique -->
      <div id="comparaison-statistique" class="scroll-mt-24 mb-16">
        <div class="flex items-center mb-6">
          <div class="w-12 h-12 rounded-full bg-gradient-to-r from-[#FF4655] to-[#3498db] flex items-center justify-center mr-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"></path><polyline points="3.27 6.96 12 12.01 20.73 6.96"></polyline><line x1="12" y1="22.08" x2="12" y2="12"></line></svg>
          </div>
          <h2 class="text-3xl font-bold bg-gradient-to-r from-[#FF4655] to-[#3498db] text-transparent bg-clip-text">Comparaison statistique</h2>
        </div>
        
        <div class="bg-[#1A242D] rounded-lg p-6 mb-8 shadow-md">
          <p class="text-gray-300 mb-6">Les chiffres ne mentent pas (enfin presque). Voici ce que nous révèlent les statistiques de 2025 sur la performance relative des duellistes et initiateurs :</p>
          
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
            <div class="bg-[#0F1923] p-4 rounded-lg">
              <h3 class="text-xl font-bold mb-4 text-[#FF4655]">Statistiques Compétitives</h3>
              
              <div class="mb-4">
                <div class="flex justify-between mb-1">
                  <span class="text-gray-300">Pick Rate Pro</span>
                </div>
                <div class="flex items-center">
                  <span class="w-16 text-center text-sm text-[#FF4655]">Duellistes</span>
                  <div class="flex-1 mx-2">
                    <div class="bg-gray-700 h-5 w-full rounded-full overflow-hidden">
                      <div class="bg-[#FF4655] h-full rounded-full" style="width: 42%"></div>
                    </div>
                  </div>
                  <span class="text-sm">42%</span>
                </div>
                <div class="flex items-center mt-1">
                  <span class="w-16 text-center text-sm text-[#3498db]">Initiateurs</span>
                  <div class="flex-1 mx-2">
                    <div class="bg-gray-700 h-5 w-full rounded-full overflow-hidden">
                      <div class="bg-[#3498db] h-full rounded-full" style="width: 38%"></div>
                    </div>
                  </div>
                  <span class="text-sm">38%</span>
                </div>
              </div>
              
              <div class="mb-4">
                <div class="flex justify-between mb-1">
                  <span class="text-gray-300">Win Rate Radiant+</span>
                </div>
                <div class="flex items-center">
                  <span class="w-16 text-center text-sm text-[#FF4655]">Duellistes</span>
                  <div class="flex-1 mx-2">
                    <div class="bg-gray-700 h-5 w-full rounded-full overflow-hidden">
                      <div class="bg-[#FF4655] h-full rounded-full" style="width: 48.5%"></div>
                    </div>
                  </div>
                  <span class="text-sm">48.5%</span>
                </div>
                <div class="flex items-center mt-1">
                  <span class="w-16 text-center text-sm text-[#3498db]">Initiateurs</span>
                  <div class="flex-1 mx-2">
                    <div class="bg-gray-700 h-5 w-full rounded-full overflow-hidden">
                      <div class="bg-[#3498db] h-full rounded-full" style="width: 51.2%"></div>
                    </div>
                  </div>
                  <span class="text-sm">51.2%</span>
                </div>
              </div>
              
              <div>
                <div class="flex justify-between mb-1">
                  <span class="text-gray-300">First Blood Rate</span>
                </div>
                <div class="flex items-center">
                  <span class="w-16 text-center text-sm text-[#FF4655]">Duellistes</span>
                  <div class="flex-1 mx-2">
                    <div class="bg-gray-700 h-5 w-full rounded-full overflow-hidden">
                      <div class="bg-[#FF4655] h-full rounded-full" style="width: 65%"></div>
                    </div>
                  </div>
                  <span class="text-sm">65%</span>
                </div>
                <div class="flex items-center mt-1">
                  <span class="w-16 text-center text-sm text-[#3498db]">Initiateurs</span>
                  <div class="flex-1 mx-2">
                    <div class="bg-gray-700 h-5 w-full rounded-full overflow-hidden">
                      <div class="bg-[#3498db] h-full rounded-full" style="width: 25%"></div>
                    </div>
                  </div>
                  <span class="text-sm">25%</span>
                </div>
              </div>
            </div>
            
            <div class="bg-[#0F1923] p-4 rounded-lg">
              <h3 class="text-xl font-bold mb-4 text-gradient-to-r from-[#FF4655] to-[#3498db]">Performance par phase de jeu</h3>
              
              <div class="space-y-3">
                <div class="bg-[#1A242D] p-3 rounded-lg">
                  <h4 class="font-medium mb-2">Early Round</h4>
                  <div class="flex items-center justify-between">
                    <div class="flex items-center">
                      <div class="w-4 h-4 bg-[#FF4655] rounded-full mr-2"></div>
                      <span class="text-sm">Duellistes</span>
                    </div>
                    <div class="w-32 bg-gray-700 rounded-full h-2">
                      <div class="bg-[#FF4655] h-2 rounded-full" style="width: 80%"></div>
                    </div>
                    <span class="text-sm">8/10</span>
                  </div>
                  <div class="flex items-center justify-between mt-2">
                    <div class="flex items-center">
                      <div class="w-4 h-4 bg-[#3498db] rounded-full mr-2"></div>
                      <span class="text-sm">Initiateurs</span>
                    </div>
                    <div class="w-32 bg-gray-700 rounded-full h-2">
                      <div class="bg-[#3498db] h-2 rounded-full" style="width: 70%"></div>
                    </div>
                    <span class="text-sm">7/10</span>
                  </div>
                </div>
                
                <div class="bg-[#1A242D] p-3 rounded-lg">
                  <h4 class="font-medium mb-2">Mid Round</h4>
                  <div class="flex items-center justify-between">
                    <div class="flex items-center">
                      <div class="w-4 h-4 bg-[#FF4655] rounded-full mr-2"></div>
                      <span class="text-sm">Duellistes</span>
                    </div>
                    <div class="w-32 bg-gray-700 rounded-full h-2">
                      <div class="bg-[#FF4655] h-2 rounded-full" style="width: 60%"></div>
                    </div>
                    <span class="text-sm">6/10</span>
                  </div>
                  <div class="flex items-center justify-between mt-2">
                    <div class="flex items-center">
                      <div class="w-4 h-4 bg-[#3498db] rounded-full mr-2"></div>
                      <span class="text-sm">Initiateurs</span>
                    </div>
                    <div class="w-32 bg-gray-700 rounded-full h-2">
                      <div class="bg-[#3498db] h-2 rounded-full" style="width: 80%"></div>
                    </div>
                    <span class="text-sm">8/10</span>
                  </div>
                </div>
                
                <div class="bg-[#1A242D] p-3 rounded-lg">
                  <h4 class="font-medium mb-2">Late Round (Clutch)</h4>
                  <div class="flex items-center justify-between">
                    <div class="flex items-center">
<div class="flex items-center justify-between">
                    <div class="flex items-center">
                      <div class="w-4 h-4 bg-[#FF4655] rounded-full mr-2"></div>
                      <span class="text-sm">Duellistes</span>
                    </div>
                    <div class="w-32 bg-gray-700 rounded-full h-2">
                      <div class="bg-[#FF4655] h-2 rounded-full" style="width: 50%"></div>
                    </div>
                    <span class="text-sm">5/10</span>
                  </div>
                  <div class="flex items-center justify-between mt-2">
                    <div class="flex items-center">
                      <div class="w-4 h-4 bg-[#3498db] rounded-full mr-2"></div>
                      <span class="text-sm">Initiateurs</span>
                    </div>
                    <div class="w-32 bg-gray-700 rounded-full h-2">
                      <div class="bg-[#3498db] h-2 rounded-full" style="width: 90%"></div>
                    </div>
                    <span class="text-sm">9/10</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
          
          <div class="bg-[#0F1923] p-5 rounded-lg">
            <h3 class="text-xl font-bold mb-4 text-white">Performance par ELO</h3>
            <div class="overflow-x-auto">
              <table class="w-full text-gray-300">
                <thead>
                  <tr>
                    <th class="text-left py-2 px-3">Rang</th>
                    <th class="text-center py-2 px-3">Win Rate Duellistes</th>
                    <th class="text-center py-2 px-3">Win Rate Initiateurs</th>
                    <th class="text-center py-2 px-3">Meilleur Choix</th>
                  </tr>
                </thead>
                <tbody>
                  <tr class="border-t border-gray-700">
                    <td class="py-2 px-3">Iron-Bronze</td>
                    <td class="text-center py-2 px-3 text-[#FF4655]">52.8%</td>
                    <td class="text-center py-2 px-3 text-[#3498db]">47.3%</td>
                    <td class="text-center py-2 px-3">
                      <span class="px-2 py-1 rounded bg-[#FF4655] bg-opacity-20 text-[#FF4655] text-xs">Duellistes</span>
                    </td>
                  </tr>
                  <tr class="border-t border-gray-700">
                    <td class="py-2 px-3">Silver-Gold</td>
                    <td class="text-center py-2 px-3 text-[#FF4655]">51.2%</td>
                    <td class="text-center py-2 px-3 text-[#3498db]">49.1%</td>
                    <td class="text-center py-2 px-3">
                      <span class="px-2 py-1 rounded bg-[#FF4655] bg-opacity-20 text-[#FF4655] text-xs">Duellistes</span>
                    </td>
                  </tr>
                  <tr class="border-t border-gray-700">
                    <td class="py-2 px-3">Platinum-Diamond</td>
                    <td class="text-center py-2 px-3 text-[#FF4655]">49.8%</td>
                    <td class="text-center py-2 px-3 text-[#3498db]">50.3%</td>
                    <td class="text-center py-2 px-3">
                      <span class="px-2 py-1 rounded bg-[#3498db] bg-opacity-20 text-[#3498db] text-xs">Initiateurs</span>
                    </td>
                  </tr>
                  <tr class="border-t border-gray-700">
                    <td class="py-2 px-3">Ascendant-Immortal</td>
                    <td class="text-center py-2 px-3 text-[#FF4655]">48.7%</td>
                    <td class="text-center py-2 px-3 text-[#3498db]">51.5%</td>
                    <td class="text-center py-2 px-3">
                      <span class="px-2 py-1 rounded bg-[#3498db] bg-opacity-20 text-[#3498db] text-xs">Initiateurs</span>
                    </td>
                  </tr>
                  <tr class="border-t border-gray-700">
                    <td class="py-2 px-3">Radiant</td>
                    <td class="text-center py-2 px-3 text-[#FF4655]">48.5%</td>
                    <td class="text-center py-2 px-3 text-[#3498db]">51.2%</td>
                    <td class="text-center py-2 px-3">
                      <span class="px-2 py-1 rounded bg-[#3498db] bg-opacity-20 text-[#3498db] text-xs">Initiateurs</span>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
        
        <div class="bg-[#1A242D] p-5 rounded-lg mb-8 border-t-4 border-purple-500">
          <h4 class="font-bold mb-2 text-purple-400">Analyse des chiffres:</h4>
          <p class="text-gray-300">Ce que ces statistiques nous révèlent est fascinant : plus vous montez en rang, plus la valeur des initiateurs augmente par rapport aux duellistes. En Iron-Bronze, installez-vous confortablement avec une Reyna et déchirez tout. En Radiant, une bonne Fade ou un Sova maîtrisé fera des miracles.</p>
          <p class="text-gray-300 mt-3">La raison est simple : à bas ELO, le skill mécanique fait la différence, tandis qu'en haut ELO, l'information et l'utilité d'équipe deviennent cruciales face à des adversaires qui ne ratent pas leurs tirs. C'est comme passer d'un film d'action sans scénario à un thriller d'espionnage complexe.</p>
          <p class="text-gray-300 mt-3 italic">"Les duellistes gagnent les rounds, les initiateurs gagnent les matchs" - Un coach pro anonyme</p>
        </div>
      </div>
      
      <!-- Choix selon carte et composition -->
      <div id="carte-comp" class="scroll-mt-24 mb-16">
        <div class="flex items-center mb-6">
          <div class="w-12 h-12 rounded-full bg-gradient-to-r from-[#FF4655] to-[#3498db] flex items-center justify-center mr-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect><line x1="3" y1="9" x2="21" y2="9"></line><line x1="9" y1="21" x2="9" y2="9"></line></svg>
          </div>
          <h2 class="text-3xl font-bold bg-gradient-to-r from-[#FF4655] to-[#3498db] text-transparent bg-clip-text">Choix selon carte et composition</h2>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
          <div class="bg-[#1A242D] rounded-lg p-5 shadow-md">
            <h3 class="text-xl font-bold mb-4 text-white flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path><polyline points="9 22 9 12 15 12 15 22"></polyline></svg>
              Cartes favorisant les Duellistes
            </h3>
            
            <div class="space-y-4">
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/icebox-icon.webp" alt="Icebox" class="w-12 h-12 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Icebox</h4>
                  <p class="text-sm text-gray-400">Les nombreuses hauteurs et angles variés permettent aux duellistes mobiles comme Jett ou Raze d'exceller.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#FF4655] text-white px-2 py-0.5 rounded">Duelliste +15%</span>
                  </div>
                </div>
              </div>
              
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/haven-icon.webp" alt="Haven" class="w-12 h-12 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Haven</h4>
                  <p class="text-sm text-gray-400">Avec trois sites, les rotations rapides et l'agressivité des duellistes peuvent mettre une pression constante.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#FF4655] text-white px-2 py-0.5 rounded">Duelliste +10%</span>
                  </div>
                </div>
              </div>
              
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/bind-icon.webp" alt="Bind" class="w-12 h-12 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Bind</h4>
                  <p class="text-sm text-gray-400">Les espaces restreints et les téléporteurs sont parfaits pour les entrées explosives de Raze et Phoenix.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#FF4655] text-white px-2 py-0.5 rounded">Duelliste +8%</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
          
          <div class="bg-[#1A242D] rounded-lg p-5 shadow-md">
            <h3 class="text-xl font-bold mb-4 text-white flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path><polyline points="9 22 9 12 15 12 15 22"></polyline></svg>
              Cartes favorisant les Initiateurs
            </h3>
            
            <div class="space-y-4">
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/ascent-icon.webp" alt="Ascent" class="w-12 h-12 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Ascent</h4>
                  <p class="text-sm text-gray-400">Le mid ouvert et les longs couloirs rendent la reconnaissance et les flashes extrêmement valorisantes.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#3498db] text-white px-2 py-0.5 rounded">Initiateur +12%</span>
                  </div>
                </div>
              </div>
              
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/fracture-icon.webp" alt="Fracture" class="w-12 h-12 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Fracture</h4>
                  <p class="text-sm text-gray-400">La structure en H nécessite une information constante que seuls les initiateurs peuvent fournir efficacement.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#3498db] text-white px-2 py-0.5 rounded">Initiateur +15%</span>
                  </div>
                </div>
              </div>
              
              <div class="bg-[#0F1923] p-3 rounded-lg flex items-start">
                <img src="https://i.postimg.cc/C5F3jL1M/pearl-icon.webp" alt="Pearl" class="w-12 h-12 mr-3 rounded-md">
                <div>
                  <h4 class="font-bold text-white">Pearl</h4>
                  <p class="text-sm text-gray-400">Les multiples angles et les zones complexes rendent les capacités de reconnaissance indispensables.</p>
                  <div class="mt-1 flex items-center">
                    <span class="text-xs bg-[#3498db] text-white px-2 py-0.5 rounded">Initiateur +10%</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <div class="bg-[#1A242D] rounded-lg p-6 mb-8 shadow-md">
          <h3 class="text-xl font-bold mb-4 text-white">Composition d'équipe optimale</h3>
          <p class="text-gray-300 mb-4">La composition idéale en 2025 s'articule généralement autour de ce schéma :</p>
          
          <div class="grid grid-cols-1 md:grid-cols-5 gap-4 mb-6">
            <div class="bg-[#0F1923] p-3 rounded-lg text-center">
              <div class="w-12 h-12 bg-[#FF4655] rounded-full mx-auto flex items-center justify-center mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"></path></svg>
              </div>
              <h4 class="font-medium">1-2 Duellistes</h4>
              <p class="text-xs text-gray-400 mt-1">Pour créer l'espace et les entrées</p>
            </div>
            
            <div class="bg-[#0F1923] p-3 rounded-lg text-center">
              <div class="w-12 h-12 bg-[#3498db] rounded-full mx-auto flex items-center justify-center mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M22 12h-4l-3 9L9 3l-3 9H2"></path></svg>
              </div>
              <h4 class="font-medium">1-2 Initiateurs</h4>
              <p class="text-xs text-gray-400 mt-1">Pour l'info et le support offensif</p>
            </div>
            
            <div class="bg-[#0F1923] p-3 rounded-lg text-center">
              <div class="w-12 h-12 bg-purple-600 rounded-full mx-auto flex items-center justify-center mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M18.364 5.636a9 9 0 0 1 0 12.728m-3.536-3.536a4 4 0 0 1 0-5.656"></path><circle cx="9" cy="15" r="6"></circle></svg>
              </div>
              <h4 class="font-medium">1 Contrôleur</h4>
              <p class="text-xs text-gray-400 mt-1">Pour les smokes et contrôle de zones</p>
            </div>
            
            <div class="bg-[#0F1923] p-3 rounded-lg text-center">
              <div class="w-12 h-12 bg-yellow-600 rounded-full mx-auto flex items-center justify-center mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path></svg>
              </div>
              <h4 class="font-medium">1 Sentinelle</h4>
              <p class="text-xs text-gray-400 mt-1">Pour la défense et l'information passive</p>
            </div>
            
            <div class="bg-[#0F1923] p-3 rounded-lg text-center">
              <div class="w-12 h-12 bg-green-600 rounded-full mx-auto flex items-center justify-center mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M8 3v3a2 2 0 0 1-2 2H3m18 0h-3a2 2 0 0 1-2-2V3m0 18v-3a2 2 0 0 1 2-2h3M3 16h3a2 2 0 0 1 2 2v3"></path></svg>
              </div>
              <h4 class="font-medium">Flex Pick</h4>
              <p class="text-xs text-gray-400 mt-1">Selon la carte et le style d'équipe</p>
            </div>
          </div>
          
          <div class="bg-[#0F1923] p-4 rounded-lg mb-4">
            <h4 class="font-medium mb-3 text-[#FF4655]">Quand maximiser les Duellistes:</h4>
            <ul class="space-y-2 text-gray-300">
              <li class="flex items-baseline">
                <span class="text-[#FF4655] mr-2">•</span>
                <span>Sur les cartes avec beaucoup de hauteurs et zones ouvertes (Icebox, Breeze)</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#FF4655] mr-2">•</span>
                <span>Quand vous jouez agressif, orienté entrées rapides</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#FF4655] mr-2">•</span>
                <span>Si votre team a des joueurs mécaniquement forts</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#FF4655] mr-2">•</span>
                <span>En duo queue avec un bon initiateur</span>
              </li>
            </ul>
          </div>
          
          <div class="bg-[#0F1923] p-4 rounded-lg">
            <h4 class="font-medium mb-3 text-[#3498db]">Quand maximiser les Initiateurs:</h4>
            <ul class="space-y-2 text-gray-300">
              <li class="flex items-baseline">
                <span class="text-[#3498db] mr-2">•</span>
                <span>Sur les cartes avec longs couloirs et nombreux angles (Ascent, Pearl)</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#3498db] mr-2">•</span>
                <span>Quand votre style est plus méthodique et basé sur l'information</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#3498db] mr-2">•</span>
                <span>En équipe complète avec bonne communication</span>
              </li>
              <li class="flex items-baseline">
                <span class="text-[#3498db] mr-2">•</span>
                <span>Contre des équipes défensives qui jouent retake</span>
              </li>
            </ul>
          </div>
        </div>
        
        <div class="bg-gradient-to-r from-[#1A242D] to-[#0F1923] p-5 rounded-lg mb-8 border-t-4 border-[#FF4655] border-r-4 border-r-[#3498db]">
          <h4 class="font-bold mb-2 text-white">L'équilibre parfait:</h4>
          <p class="text-gray-300">La vérité que les pros connaissent depuis longtemps: une composition avec 1 duelliste + 2 initiateurs est souvent optimale. Le duelliste crée l'espace, les initiateurs maximisent cet espace avec information et utilité. C'est comme un bon mariage - le duelliste fait le show, l'initiateur fait en sorte que le show soit un succès.</p>
          <p class="text-gray-300 mt-3">Notez toutefois qu'en SoloQ, jusqu'au Diamond environ, deux duellistes peuvent être plus efficaces en raison du manque de coordination et de communication. Parfois, brute force > stratégie élaborée.</p>
        </div>
      </div>
      
      <!-- Méta actuelle -->
      <div id="meta-actuelle" class="scroll-mt-24 mb-16">
        <div class="flex items-center mb-6">
          <div class="w-12 h-12 rounded-full bg-gradient-to-r from-[#FF4655] to-[#3498db] flex items-center justify-center mr-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><line x1="2" y1="12" x2="22" y2="12"></line><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"></path></svg>
          </div>
          <h2 class="text-3xl font-bold bg-gradient-to-r from-[#FF4655] to-[#3498db] text-transparent bg-clip-text">Méta actuelle (2025)</h2>
        </div>
        
        <div class="bg-[#1A242D] rounded-lg p-6 mb-8 shadow-md">
          <p class="text-gray-300 mb-6">La méta de 2025 a considérablement évolué depuis les premiers jours de Valorant. Voici ce qui définit le paysage compétitif actuel :</p>
          
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
            <div class="bg-[#0F1923] rounded-lg overflow-hidden">
              <div class="bg-[#FF4655] bg-opacity-10 p-4">
                <h3 class="text-xl font-bold text-[#FF4655]">Évolution des Duellistes</h3>
              </div>
              <div class="p-4">
                <p class="text-gray-300 mb-4">Les duellistes ont évolué d'un rôle purement agressif vers un rôle plus tactique :</p>
                <ul class="space-y-3 text-gray-300">
                  <li class="flex items-start">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#FF4655] mr-2 mt-1"><path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
                    <span>Moins d'entrées "suicide", plus d'entrées calculées avec utility</span>
                  </li>
                  <li class="flex items-start">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#FF4655] mr-2 mt-1"><path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
                    <span>Préférence pour les duellistes avec utility utilisable par l'équipe</span>
                  </li>
                  <li class="flex items-start">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#FF4655] mr-2 mt-1"><path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
                    <span>Un seul duelliste est devenu la norme en pro play</span>
                  </li>
                  <li class="flex items-start">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#FF4655] mr-2 mt-1"><path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
                    <span>Les joueurs de Jett ont développé un ego proportionnel à leur skill</span>
                  </li>
                </ul>
              </div>
            </div>
            
            <div class="bg-[#0F1923] rounded-lg overflow-hidden">
              <div class="bg-[#3498db] bg-opacity-10 p-4">
                <h3 class="text-xl font-bold text-[#3498db]">Évolution des Initiateurs</h3>
              </div>
              <div class="p-4">
                <p class="text-gray-300 mb-4">Les initiateurs sont passés de simples supports à des piliers essentiels :</p>
                <ul class="space-y-3 text-gray-300">
                  <li class="flex items-start">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#3498db] mr-2 mt-1"><path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
                    <span>Plus grande valorisation des capacités de clearing et reconquest</span>
                  </li>
                  <li class="flex items-start">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#3498db] mr-2 mt-1"><path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
                    <span>Augmentation du nombre d'initiateurs par équipe (souvent 2)</span>
                  </li>
                  <li class="flex items-start">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#3498db] mr-2 mt-1"><path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
<span>Développement des stratégies basées sur l'information multi-angles</span>
                  </li>
                  <li class="flex items-start">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-[#3498db] mr-2 mt-1"><path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
                    <span>Adoption massive des initiateurs "hybrides" qui peuvent aussi fragger</span>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          
          <div class="bg-[#0F1923] rounded-lg p-5 mb-6">
            <h3 class="text-xl font-bold mb-4 text-white">Tendances pro 2025</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
              <div class="bg-[#1A242D] p-3 rounded-lg">
                <h4 class="font-medium mb-2 text-[#FF4655]">Équipes NA/EMEA</h4>
                <p class="text-sm text-gray-300 mb-2">Tendance: <span class="text-white">1 Duelliste + 2 Initiateurs</span></p>
                <p class="text-xs text-gray-400">Les équipes occidentales optent pour des compositions équilibrées avec un seul duelliste fort et deux initiateurs pour maximiser l'information.</p>
              </div>
              
              <div class="bg-[#1A242D] p-3 rounded-lg">
                <h4 class="font-medium mb-2 text-[#FF4655]">Équipes APAC</h4>
                <p class="text-sm text-gray-300 mb-2">Tendance: <span class="text-white">2 Duellistes + 1 Initiateur</span></p>
                <p class="text-xs text-gray-400">Les équipes asiatiques privilégient encore l'agressivité avec deux duellistes, compensant par une execution parfaite et un timing impeccable.</p>
              </div>
              
              <div class="bg-[#1A242D] p-3 rounded-lg">
                <h4 class="font-medium mb-2 text-[#FF4655]">Équipes BR/LATAM</h4>
                <p class="text-sm text-gray-300 mb-2">Tendance: <span class="text-white">1.5 Duellistes + 1.5 Initiateurs</span></p>
                <p class="text-xs text-gray-400">Style hybride avec des picks flex (agents pouvant jouer entre les deux rôles) et des stratégies imprévisibles adaptées à chaque map.</p>
              </div>
            </div>
          </div>
          
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="bg-[#0F1923] p-4 rounded-lg">
              <h3 class="text-xl font-bold mb-3 text-white">Les hybrides qui définissent 2025</h3>
              <p class="text-gray-300 mb-4">La frontière entre duellistes et initiateurs s'estompe avec des agents qui combinent les deux aspects :</p>
              
              <div class="space-y-3">
                <div class="bg-[#1A242D] p-3 rounded-lg flex items-start">
                  <img src="https://i.postimg.cc/C5F3jL1M/phoenix-icon.webp" alt="Phoenix" class="w-10 h-10 mr-3 rounded-md">
                  <div>
                    <h4 class="font-bold text-white">Phoenix</h4>
                    <p class="text-sm text-gray-400">Après ses buffs massifs, Phoenix combine les flashes d'un initiateur avec la mobilité d'un duelliste. Le meilleur des deux mondes.</p>
                  </div>
                </div>
                
                <div class="bg-[#1A242D] p-3 rounded-lg flex items-start">
                  <img src="https://i.postimg.cc/C5F3jL1M/gekko-icon.webp" alt="Gekko" class="w-10 h-10 mr-3 rounded-md">
                  <div>
                    <h4 class="font-bold text-white">Gekko</h4>
                    <p class="text-sm text-gray-400">Sa capacité à récupérer son utilité lui permet d'alterner entre rôle d'information et entrée agressive.</p>
                  </div>
                </div>
                
                <div class="bg-[#1A242D] p-3 rounded-lg flex items-start">
                  <img src="https://i.postimg.cc/C5F3jL1M/kayo-icon.webp" alt="KAY/O" class="w-10 h-10 mr-3 rounded-md">
                  <div>
                    <h4 class="font-bold text-white">KAY/O</h4>
                    <p class="text-sm text-gray-400">Ses flashes permettent des entrées de duelliste tandis que ses capacités de suppression sont typiques d'un initiateur.</p>
                  </div>
                </div>
              </div>
            </div>
            
            <div class="bg-[#0F1923] p-4 rounded-lg">
              <h3 class="text-xl font-bold mb-3 text-white">Prédictions pour fin 2025</h3>
              <p class="text-gray-300 mb-4">Où se dirige la méta d'ici la fin de l'année :</p>
              
              <ul class="space-y-3 text-gray-300">
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-yellow-400 mr-2 mt-1"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
                  <span>L'équilibre global continuera de pencher vers les initiateurs dans les plus hauts niveaux</span>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-yellow-400 mr-2 mt-1"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
                  <span>De nouveaux agents hybrides brouillant davantage la frontière entre les rôles</span>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-yellow-400 mr-2 mt-1"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
                  <span>Les compositions avec un seul duelliste deviendront la norme à tous les niveaux</span>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-yellow-400 mr-2 mt-1"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
                  <span>Les duellistes évolueront pour inclure plus d'utilité d'équipe dans leurs kits</span>
                </li>
                <li class="flex items-start">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-yellow-400 mr-2 mt-1"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
                  <span>Les initiateurs acquerront plus d'outils d'entrée autonomes</span>
                </li>
              </ul>
              
              <div class="mt-4 p-3 bg-[#1A242D] rounded-lg border-l-4 border-yellow-500">
                <p class="text-yellow-400 font-bold text-sm">PRÉDICTION AUDACIEUSE:</p>
                <p class="text-gray-300 text-sm mt-1">D'ici fin 2025, nous verrons des équipes pro expérimenter avec des compositions sans duelliste sur certaines cartes, remplacés par des initiateurs agressifs.</p>
              </div>
            </div>
          </div>
        </div>
        
        <div class="bg-[#1A242D] p-5 rounded-lg mb-8 border-t-4 border-gradient-to-r from-[#FF4655] to-[#3498db]">
          <h4 class="font-bold mb-2 text-white">Le mot d'un pro:</h4>
          <blockquote class="text-gray-300 italic">
            "La différence entre 2020 et 2025? Avant, les duellistes portaient leurs équipes. Maintenant, les équipes portent un duelliste pour qu'il puisse briller. Le jeu a évolué vers plus de tactique, et les initiateurs sont au cœur de cette transformation."
          </blockquote>
          <p class="text-right text-gray-400 mt-2">— TenZ, après sa transition de Jett à Sova en 2024</p>
        </div>
      </div>
      
      <!-- Conclusion et recommandations -->
      <div id="conclusion" class="scroll-mt-24">
        <div class="flex items-center mb-6">
          <div class="w-12 h-12 rounded-full bg-gradient-to-r from-[#FF4655] to-[#3498db] flex items-center justify-center mr-3">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path><polyline points="22 4 12 14.01 9 11.01"></polyline></svg>
          </div>
          <h2 class="text-3xl font-bold bg-gradient-to-r from-[#FF4655] to-[#3498db] text-transparent bg-clip-text">Conclusion et recommandations</h2>
        </div>
        
        <div class="bg-gradient-to-r from-[#1A242D] to-[#0F1923] rounded-lg p-6 mb-8 shadow-md border-b-4 border-gradient-to-r from-[#FF4655] to-[#3498db]">
          <p class="text-xl text-gray-300 mb-4 leading-relaxed">
            Après cette analyse approfondie, il est clair qu'il n'y a pas de réponse universelle à la question "duelliste ou initiateur". Chaque rôle a ses forces, ses faiblesses, et son moment pour briller. Le choix optimal dépend d'une multitude de facteurs: votre rang, votre style de jeu, la carte, la composition de votre équipe, et même l'heure de la journée (oui, les duellistes sont encore plus toxiques après minuit).
          </p>
          
          <p class="text-xl text-gray-300 mb-4 leading-relaxed">
            Ce qui est certain, c'est que Valorant est devenu un jeu où l'information et l'utilité d'équipe prennent de plus en plus d'importance. Les jours où cinq duellistes pouvaient gagner par pure force brute sont révolus (sauf peut-être en Iron, où cinq Reynas continuent de se battre pour l'orbe ultime).
          </p>
          
          <p class="text-xl text-gray-300 mb-4 leading-relaxed">
            La tendance est claire: plus vous montez en rang, plus les initiateurs gagnent en valeur. Mais ne vous y trompez pas - un duelliste bien joué reste une force terrifiante capable de porter des rounds entiers sur ses épaules.
          </p>
          
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-8">
            <div class="bg-[#0F1923] p-5 rounded-lg border-l-4 border-[#FF4655]">
              <h3 class="text-lg font-bold mb-3 text-[#FF4655]">Choisissez un Duelliste si...</h3>
              <ul class="space-y-2 text-gray-300">
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>Vous avez confiance en votre aim et vos réflexes</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>Vous aimez être le premier à entrer et créer des opportunités</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>Vous jouez en SoloQ à bas/moyen ELO</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>Votre équipe manque d'entrées et d'agressivité</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>La carte favorise la mobilité et les plays verticaux</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#FF4655] mr-2">•</span>
                  <span>Vous rêvez d'apparaître dans des compilations YouTube</span>
                </li>
              </ul>
            </div>
            
            <div class="bg-[#0F1923] p-5 rounded-lg border-l-4 border-[#3498db]">
              <h3 class="text-lg font-bold mb-3 text-[#3498db]">Choisissez un Initiateur si...</h3>
              <ul class="space-y-2 text-gray-300">
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>Vous valorisez l'impact d'équipe plus que les stats personnelles</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>Vous excellez dans l'analyse tactique et la prise d'information</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>Vous jouez en équipe organisée ou à haut ELO</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>Votre équipe a déjà un (ou plusieurs) duellistes</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>La carte comporte de longs couloirs et de nombreux angles</span>
                </li>
                <li class="flex items-baseline">
                  <span class="text-[#3498db] mr-2">•</span>
                  <span>Vous préférez gagner plutôt qu'avoir un KDA impressionnant</span>
                </li>
              </ul>
            </div>
          </div>
          
          <div class="mt-8 p-5 bg-[#0F1923] rounded-lg">
            <h3 class="text-xl font-bold mb-4 text-white">Notre conseil final:</h3>
            <p class="text-gray-300">Maîtrisez au moins un agent de chaque catégorie. La polyvalence est la clé dans Valorant 2025. Savoir quand être le héros duelliste et quand être le cerveau initiateur fera de vous un joueur complet et adaptatif. Et rappelez-vous, le meilleur agent est celui que vous prenez plaisir à jouer - car au final, c'est bien pour ça qu'on joue, non?</p>
            <p class="text-gray-300 mt-4 italic text-center">"Les duellistes gagnent des rounds, les initiateurs gagnent des matchs, mais c'est l'équilibre entre les deux qui gagne des championnats."</p>
          </div>
        </div>
        
        <!-- Section commentaires et social -->
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
          <div class="bg-[#1A242D] rounded-lg p-5 shadow-md">
            <h3 class="font-bold mb-4 flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"></path></svg>
              Laisser un commentaire
            </h3>
            <div class="flex mb-4">
              <div class="w-10 h-10 rounded-full bg-gray-700 flex items-center justify-center mr-3 text-gray-400">
                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
              </div>
              <div class="flex-1">
                <textarea placeholder="Partagez votre opinion sur le débat Duellistes vs Initiateurs..." class="w-full bg-[#0F1923] border border-gray-700 rounded-md p-3 text-white resize-none focus:outline-none focus:border-gradient-to-r from-[#FF4655] to-[#3498db] transition-colors" rows="3"></textarea>
              </div>
            </div>
            <div class="flex justify-end">
              <button class="px-4 py-2 bg-gradient-to-r from-[#FF4655] to-[#3498db] hover:bg-opacity-90 text-white rounded-md transition-colors">Publier</button>
            </div>
          </div>
          
          <div class="bg-[#1A242D] rounded-lg p-5 shadow-md">
            <h3 class="font-bold mb-4 flex items-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path></svg>
              Partager cet article
            </h3>
            <div class="flex space-x-3 mb-4">
              <a href="#" class="w-10 h-10 rounded-full bg-[#0F1923] hover:bg-gradient-to-r from-[#FF4655] to-[#3498db] flex items-center justify-center text-white transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path></svg>
              </a>
              <a href="#" class="w-10 h-10 rounded-full bg-[#0F1923] hover:bg-gradient-to-r from-[#FF4655] to-[#3498db] flex items-center justify-center text-white transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"></path></svg>
              </a>
              <a href="#" class="w-10 h-10 rounded-full bg-[#0F1923] hover:bg-gradient-to-r from-[#FF4655] to-[#3498db] flex items-center justify-center text-white transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
              </a>
              <a href="#" class="w-10 h-10 rounded-full bg-[#0F1923] hover:bg-gradient-to-r from-[#FF4655] to-[#3498db] flex items-center justify-center text-white transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg>
              </a>
              <a href="#" class="w-10 h-10 rounded-full bg-[#0F1923] hover:bg-gradient-to-r from-[#FF4655] to-[#3498db] flex items-center justify-center text-white transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.25 29 29 0 0 0-.46-5.33z"></path><polygon points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02"></polygon></svg>
              </a>
            </div>
            <div class="pt-4 border-t border-gray-700">
              <h4 class="font-medium mb-3">Articles liés</h4>
              <ul class="space-y-2 text-gray-300">
                <li>
                  <a href="#" class="hover:text-gradient-to-r from-[#FF4655] to-[#3498db] transition-colors flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M9 18l6-6-6-6"></path></svg>
                    Guide complet de Jett: Pourquoi elle domine le méta actuel (2025)
                  </a>
                </li>
                <li>
                  <a href="#" class="hover:text-gradient-to-r from-[#FF4655] to-[#3498db] transition-colors flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M9 18l6-6-6-6"></path></svg>
                    Les meilleures synergies duellistes-initiateurs en 2025
                  </a>
                </li>
                <li>
                  <a href="#" class="hover:text-gradient-to-r from-[#FF4655] to-[#3498db] transition-colors flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="mr-2"><path d="M9 18l6-6-6-6"></path></svg>
                    Guide complet pour maîtriser Ascent sur Valorant
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        
        <!-- Call to Action -->
        <div class="bg-gradient-to-r from-[#FF4655] to-[#3498db] rounded-lg p-6 shadow-lg transform hover:scale-102 transition-transform">
          <div class="flex flex-col md:flex-row items-center justify-between">
            <div class="mb-4 md:mb-0">
              <h3 class="text-2xl font-bold text-white mb-2">Vous avez aimé cet article?</h3>
              <p class="text-white text-opacity-90">Inscrivez-vous à notre newsletter pour recevoir nos analyses méta hebdomadaires et progresser dans Valorant!</p>
            </div>
            <div class="flex">
              <input type="email" placeholder="Votre email" class="bg-white bg-opacity-20 text-white placeholder-white placeholder-opacity-70 border-0 rounded-l-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-white" />
              <button class="bg-white text-[#FF4655] px-4 py-2 rounded-r-md font-medium hover:bg-opacity-90 transition-colors">S'inscrire</button>
            </div>
          </div>
        </div>
      </div>
    </article>
  </div>
</main>
