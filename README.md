<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aapke Liye Meli Pyali Patni Jii ❤️</title>
  
  <!-- Tailwind CSS for high-quality responsive utility styling -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Poppins for elegant modern UI, Great Vibes for premium script calligraphy -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:ital,wght@0,300;0,400;0,600;0,700;1,400&display=swap" rel="stylesheet">
  <!-- FontAwesome for romantic luxury icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            poppins: ['Poppins', 'sans-serif'],
            cursive: ['Great Vibes', 'cursive'],
          },
          colors: {
            roseGold: '#B76E79',
            luxuryGold: '#D4AF37',
            deepVelvet: '#2C0219',
            romanticPink: '#FF758F',
            glowingRed: '#FF003C',
          }
        }
      }
    }
  </script>

  <style>
    /* Custom Scrollbar */
    ::-webkit-scrollbar {
      width: 8px;
    }
    ::-webkit-scrollbar-track {
      background: #0d0214;
    }
    ::-webkit-scrollbar-thumb {
      background: linear-gradient(to bottom, #FF758F, #D4AF37);
      border-radius: 10px;
    }

    /* Core Glassmorphism Base styling */
    .glassmorphism {
      background: rgba(20, 5, 25, 0.65);
      backdrop-filter: blur(14px);
      -webkit-backdrop-filter: blur(14px);
      border: 1px solid rgba(255, 215, 0, 0.15);
      box-shadow: 0 8px 32px 0 rgba(255, 117, 143, 0.15);
    }

    .glassmorphism-light {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.1);
    }

    /* Cinematic Animated Radial Background */
    body {
      background: radial-gradient(circle at 50% 50%, #200424 0%, #0d0214 70%, #040007 100%);
      overflow-x: hidden;
    }

    /* 3D Perspective Context */
    .perspective-1000 {
      perspective: 1000px;
    }

    /* Floating Animations */
    @keyframes floating-slow {
      0%, 100% { transform: translateY(0px) rotate(0deg); }
      50% { transform: translateY(-15px) rotate(2deg); }
    }
    .animate-float-slow {
      animation: floating-slow 6s ease-in-out infinite;
    }

    /* Pulse Glow Animation */
    @keyframes pulse-glow {
      0%, 100% { transform: scale(1); filter: drop-shadow(0 0 10px rgba(255, 0, 60, 0.6)); }
      50% { transform: scale(1.05); filter: drop-shadow(0 0 30px rgba(255, 0, 60, 0.9)) drop-shadow(0 0 40px rgba(212, 175, 55, 0.4)); }
    }
    .animate-pulse-glow {
      animation: pulse-glow 3s cubic-bezier(0.4, 0, 0.6, 1) infinite;
    }

    /* Shiny Shimmer text effect */
    .shimmer-text {
      background: linear-gradient(to right, #FFF 20%, #D4AF37 40%, #FF758F 60%, #FFF 80%);
      background-size: 200% auto;
      color: transparent;
      -webkit-background-clip: text;
      background-clip: text;
      animation: shine 4s linear infinite;
    }
    @keyframes shine {
      to { background-position: 200% center; }
    }

    /* 3D Gift Box Styling */
    .gift-container {
      width: 200px;
      height: 200px;
      position: relative;
      transform-style: preserve-3d;
      transition: transform 1.5s cubic-bezier(0.25, 1, 0.5, 1);
    }
    .gift-container:hover {
      transform: rotateY(15deg) rotateX(10deg);
    }
    .gift-box-3d {
      width: 100%;
      height: 100%;
      position: absolute;
      transform-style: preserve-3d;
      animation: spinBox 20s infinite linear;
    }
    @keyframes spinBox {
      0% { transform: rotateY(0deg); }
      100% { transform: rotateY(360deg); }
    }
    .box-face {
      position: absolute;
      width: 200px;
      height: 200px;
      background: linear-gradient(135deg, #a11b3c, #590417);
      border: 4px solid #D4AF37;
      box-shadow: inset 0 0 30px rgba(0,0,0,0.6);
      backface-visibility: visible;
    }
    /* Ribbon overlays on faces */
    .box-face::after {
      content: '';
      position: absolute;
      background: linear-gradient(to right, #D4AF37, #F3E5AB, #D4AF37);
      box-shadow: 0 0 8px rgba(212, 175, 55, 0.5);
    }
    .face-v::after {
      top: 0; left: 85px; width: 30px; height: 100%;
    }
    .face-h::after {
      top: 85px; left: 0; width: 100%; height: 30px;
    }
    /* Positioning faces in 3D Space */
    .face-front  { transform: rotateY(  0deg) translateZ(100px); }
    .face-back   { transform: rotateY(180deg) translateZ(100px); }
    .face-right  { transform: rotateY( 90deg) translateZ(100px); }
    .face-left   { transform: rotateY(-90deg) translateZ(100px); }
    .face-top    { 
      transform: rotateX( 90deg) translateZ(100px); 
      background: #bf2148;
      transform-origin: top;
      transition: transform 1s cubic-bezier(0.25, 1, 0.5, 1);
    }
    .face-bottom { transform: rotateX(-90deg) translateZ(100px); background: #3d020e; }

    /* Gift Box Open state trigger */
    .gift-opened .face-top {
      transform: rotateX(90deg) translateZ(100px) rotateX(-120deg);
    }
    .gift-opened .face-front { transform: rotateY(0deg) translateZ(100px) rotateX(90deg); transform-origin: bottom; }
    .gift-opened .face-back { transform: rotateY(180deg) translateZ(100px) rotateX(90deg); transform-origin: bottom; }
    .gift-opened .face-left { transform: rotateY(-90deg) translateZ(100px) rotateX(90deg); transform-origin: bottom; }
    .gift-opened .face-right { transform: rotateY(90deg) translateZ(100px) rotateX(90deg); transform-origin: bottom; }

    /* 3D Envelope Container */
    .envelope-wrapper {
      position: relative;
      width: 100%;
      max-width: 450px;
      height: 300px;
      perspective: 1000px;
      cursor: pointer;
    }
    .envelope {
      position: absolute;
      width: 100%;
      height: 100%;
      background: #7a0928;
      border-radius: 8px;
      box-shadow: 0 10px 40px rgba(0,0,0,0.5);
      transform-style: preserve-3d;
      transition: transform 0.8s ease;
    }
    /* Flaps design */
    .flap-top {
      position: absolute;
      top: 0; left: 0; width: 0; height: 0;
      border-left: 225px solid transparent;
      border-right: 225px solid transparent;
      border-top: 150px solid #a81339;
      transform-origin: top;
      transition: transform 0.5s ease 0.4s;
      z-index: 4;
    }
    @media (max-width: 500px) {
      .flap-top {
        border-left-width: 175px; border-right-width: 175px; border-top-width: 110px;
      }
    }
    .flap-sides {
      position: absolute;
      bottom: 0; left: 0; width: 0; height: 0;
      border-left: 225px solid #63051e;
      border-right: 225px solid #63051e;
      border-bottom: 150px solid transparent;
      z-index: 3;
    }
    @media (max-width: 500px) {
      .flap-sides {
        border-left-width: 175px; border-right-width: 175px;
      }
    }
    .flap-bottom {
      position: absolute;
      bottom: 0; left: 0; width: 0; height: 0;
      border-left: 225px solid transparent;
      border-right: 225px solid transparent;
      border-bottom: 150px solid #520216;
      border-radius: 0 0 8px 8px;
      z-index: 3;
    }
    @media (max-width: 500px) {
      .flap-bottom {
        border-left-width: 175px; border-right-width: 175px; border-bottom-width: 110px;
      }
    }
    /* Letter card inside */
    .letter-card {
      position: absolute;
      top: 10px; left: 15px;
      width: calc(100% - 30px);
      height: 260px;
      background: #fdfaf2;
      border-radius: 4px;
      padding: 24px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      z-index: 2;
      transition: transform 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
      color: #310411;
      overflow-y: auto;
    }
    /* Hover/Open States */
    .envelope-wrapper.open .flap-top {
      transform: rotateX(180deg);
      z-index: 1;
    }
    .envelope-wrapper.open .letter-card {
      transform: translateY(-160px) scale(1.05);
      z-index: 5;
      height: 380px;
      box-shadow: 0 15px 40px rgba(0,0,0,0.6);
    }

    /* 3D Promise Flip Cards */
    .promise-card-inner {
      transition: transform 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275);
      transform-style: preserve-3d;
    }
    .promise-card:hover .promise-card-inner {
      transform: rotateY(180deg);
    }
    .promise-front, .promise-back {
      position: absolute;
      width: 100%;
      height: 100%;
      backface-visibility: hidden;
      border-radius: 16px;
    }
    .promise-back {
      transform: rotateY(180deg);
    }

    /* Polaroids scattered effect */
    .polaroid {
      background: white;
      padding: 12px 12px 24px 12px;
      box-shadow: 0 12px 30px rgba(0,0,0,0.4);
      transform: rotate(var(--rotation));
      transition: all 0.4s ease;
    }
    .polaroid:hover {
      transform: rotate(0deg) scale(1.08) translateY(-10px);
      z-index: 40;
      box-shadow: 0 20px 45px rgba(255, 117, 143, 0.3);
    }
  </style>
</head>
<body class="font-poppins text-white select-none">

  <!-- Ambient Stars & Heart Dust Canvas -->
  <canvas id="ambientCanvas" class="fixed top-0 left-0 w-full h-full pointer-events-none z-0"></canvas>
  
  <!-- Interactive Particle/Celebration Fireworks Canvas -->
  <canvas id="celebrationCanvas" class="fixed top-0 left-0 w-full h-full pointer-events-none z-40"></canvas>

  <!-- Cinematic Sound Controller (Web Audio Procedural Synth) -->
  <div class="fixed top-6 right-6 z-50 flex items-center gap-3">
    <button id="musicToggleBtn" class="bg-black/40 border border-luxuryGold/40 p-4 rounded-full text-luxuryGold backdrop-blur-md shadow-lg hover:scale-115 active:scale-95 transition-all flex items-center justify-center w-12 h-12" aria-label="Toggle Romance Music">
      <i id="musicIcon" class="fas fa-volume-mute text-lg"></i>
    </button>
    <div id="musicToast" class="bg-black/60 border border-romanticPink/30 text-white/90 text-xs py-1.5 px-3 rounded-lg hidden opacity-0 transition-opacity duration-300 pointer-events-none">
      🎶 Ambient Synth Active!
    </div>
  </div>

  <!-- STEP 1: Magical Landing & Gift Box Area -->
  <div id="landingScreen" class="fixed inset-0 z-50 flex flex-col justify-center items-center bg-radial from-[#1e0321] to-[#040008] transition-all duration-1000">
    
    <!-- Sparkle Loader -->
    <div id="boxLoader" class="flex flex-col items-center mb-8">
      <div class="relative w-20 h-20 flex items-center justify-center">
        <i class="fas fa-heart text-glowingRed text-5xl animate-ping absolute opacity-60"></i>
        <i class="fas fa-heart text-romanticPink text-4xl relative z-10 animate-pulse"></i>
      </div>
      <p class="text-luxuryGold tracking-widest text-xs uppercase font-semibold mt-4 animate-pulse">Pre-loading magical moments...</p>
    </div>

    <!-- Hidden gift structure, becomes visible after 2s loading -->
    <div id="giftWrapper" class="hidden flex-col items-center text-center animate-fade-in px-4">
      <h2 class="text-3xl md:text-5xl font-cursive text-luxuryGold mb-2 font-bold shimmer-text">You hold a key to my heart...</h2>
      <p class="text-sm text-pink-200/70 tracking-wide mb-12 uppercase">Please open your magical gift below</p>

      <!-- 3D Golden Gift Box Container -->
      <div class="perspective-1000 mb-16">
        <div id="interactiveGiftContainer" class="gift-container cursor-pointer">
          <div id="giftBox" class="gift-box-3d">
            <div class="box-face face-front face-v"></div>
            <div class="box-face face-back face-v"></div>
            <div class="box-face face-left face-h"></div>
            <div class="box-face face-right face-h"></div>
            <div class="box-face face-top face-v face-h"></div>
            <div class="box-face face-bottom"></div>
          </div>
        </div>
      </div>

      <!-- Hint action button -->
      <button id="giftOpenBtn" class="bg-gradient-to-r from-luxuryGold via-yellow-300 to-roseGold text-deepVelvet font-bold py-3.5 px-8 rounded-full shadow-2xl hover:scale-105 active:scale-95 transition-all uppercase tracking-wider text-xs border border-white/20 animate-bounce">
        🎁 Tap to Open Mela Bacchaaa
      </button>
    </div>
  </div>

  <!-- STEP 2: Main Romantic Dashboard / Cinematic Experience -->
  <main id="mainContent" class="relative z-10 hidden opacity-0 transition-opacity duration-1500 max-w-6xl mx-auto px-4 md:px-8 py-12">
    
    <!-- Hero / Confession Heading Section -->
    <header class="text-center min-h-[90vh] flex flex-col justify-center items-center py-16">
      <div class="glassmorphism p-8 md:p-14 rounded-3xl max-w-3xl border-luxuryGold/20 animate-float-slow relative">
        <!-- Floating decorative glowing objects inside glass -->
        <span class="absolute -top-6 -left-6 text-luxuryGold text-4xl rotate-12 opacity-60"><i class="fas fa-crown"></i></span>
        <span class="absolute -bottom-6 -right-6 text-pink-400 text-4xl -rotate-12 opacity-60"><i class="fas fa-heart"></i></span>
        
        <h1 class="text-5xl md:text-8xl font-cursive text-luxuryGold shimmer-text font-bold mb-4 drop-shadow-[0_4px_10px_rgba(0,0,0,0.8)]">
        Aapke Liye Meli Pyali Patni Jii ❤️
        </h1>
        <p class="text-xl md:text-3xl font-light tracking-wide text-pink-100 font-poppins italic">
          "Every heartbeat of mine belongs to you."
        </p>
        
        <div class="mt-8 flex justify-center gap-2 text-pink-400">
          <i class="fas fa-star text-xs animate-pulse"></i>
          <i class="fas fa-heart text-sm mx-1 animate-ping"></i>
          <i class="fas fa-star text-xs animate-pulse"></i>
        </div>
      </div>
      
      <!-- Scroll Indicator arrow down -->
      <div class="mt-16 animate-bounce text-pink-300/60 flex flex-col items-center">
        <span class="text-xs uppercase tracking-widest mb-2 font-semibold">Scroll Down to My Heart</span>
        <i class="fas fa-chevron-down text-lg"></i>
      </div>
    </header>

    <!-- SECTION 1: Our Love Story Timeline -->
    <section class="py-24 relative">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-6xl font-cursive text-luxuryGold">Our Love Story</h2>
        <div class="h-[1px] w-40 bg-gradient-to-r from-transparent via-luxuryGold to-transparent mx-auto mt-2"></div>
      </div>

      <div class="relative wrap overflow-hidden p-4 md:p-10 h-full">
        <!-- Vertical Central line -->
        <div class="border-2-2 absolute border-opacity-20 border-luxuryGold h-full border-dashed" style="left: 50%"></div>
        
        <!-- Timeline Item 1 -->
        <div class="mb-12 flex justify-between items-center w-full right-timeline flex-col md:flex-row md:even:flex-row-reverse">
          <div class="order-1 w-full md:w-5/12"></div>
          <div class="z-20 flex items-center order-1 bg-luxuryGold shadow-xl w-10 h-10 rounded-full justify-center border-2 border-pink-400/50">
            <i class="fas fa-eye text-deepVelvet text-sm"></i>
          </div>
          <div class="order-1 glassmorphism rounded-2xl w-full md:w-5/12 px-6 py-6 mt-4 md:mt-0 shadow-xl border border-pink-400/10 hover:border-luxuryGold/40 transition-all">
            <span class="text-luxuryGold font-bold text-sm tracking-widest block mb-2"><i class="far fa-calendar-alt mr-2"></i>THE FIRST SIGHT</span>
            <h3 class="text-xl font-bold text-pink-300 mb-2">Our Worlds Collided</h3>
            <p class="text-sm leading-relaxed text-pink-100/80">
              The exact moment my eyes found yours, the world seemed to fade into silence. In that fleeting second, my heart knew it had found its home.
            </p>
          </div>
        </div>

        <!-- Timeline Item 2 -->
        <div class="mb-12 flex justify-between items-center w-full left-timeline flex-col md:flex-row md:even:flex-row-reverse">
          <div class="order-1 w-full md:w-5/12"></div>
          <div class="z-20 flex items-center order-1 bg-glowingRed shadow-xl w-10 h-10 rounded-full justify-center border-2 border-luxuryGold/50">
            <i class="fas fa-heart text-white text-sm"></i>
          </div>
          <div class="order-1 glassmorphism rounded-2xl w-full md:w-5/12 px-6 py-6 mt-4 md:mt-0 shadow-xl border border-pink-400/10 hover:border-luxuryGold/40 transition-all">
            <span class="text-luxuryGold font-bold text-sm tracking-widest block mb-2"><i class="far fa-calendar-alt mr-2"></i>THE PROPOSAL</span>
            <h3 class="text-xl font-bold text-pink-300 mb-2">Saying Yes to Forever</h3>
            <p class="text-sm leading-relaxed text-pink-100/80">
              Looking into your eyes, asking you to share your beautiful life with me. Your tears of joy and that sweet 'Yes' remains the greatest victory of my entire life mela bacchaaa.
            </p>
          </div>
        </div>

        <!-- Timeline Item 3 -->
        <div class="mb-12 flex justify-between items-center w-full right-timeline flex-col md:flex-row md:even:flex-row-reverse">
          <div class="order-1 w-full md:w-5/12"></div>
          <div class="z-20 flex items-center order-1 bg-luxuryGold shadow-xl w-10 h-10 rounded-full justify-center border-2 border-pink-400/50">
            <i class="fas fa-ring text-deepVelvet text-sm"></i>
          </div>
          <div class="order-1 glassmorphism rounded-2xl w-full md:w-5/12 px-6 py-6 mt-4 md:mt-0 shadow-xl border border-pink-400/10 hover:border-luxuryGold/40 transition-all">
            <span class="text-luxuryGold font-bold text-sm tracking-widest block mb-2"><i class="far fa-calendar-alt mr-2"></i>OUR WEDDING DAY</span>
            <h3 class="text-xl font-bold text-pink-300 mb-2">My Wife, My Destiny</h3>
            <p class="text-sm leading-relaxed text-pink-100/80">
              Standing together, hands intertwined, making vows before the universe. That day, you didn't just become my wife; you became my sacred forever meli pyali biwi jii.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- SECTION 2: Reasons Why I Love You Mela Pyala Bacchaaa-->
    <section class="py-24 relative">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-6xl font-cursive text-luxuryGold">Why I Love You</h2>
        <p class="text-pink-300/70 text-sm uppercase tracking-wider mt-2">Just a few of the infinite reasons my heart beats for you mela chota sa pyala sa cutu sa mela bacchaaa</p>
        <div class="h-[1px] w-40 bg-gradient-to-r from-transparent via-luxuryGold to-transparent mx-auto mt-2"></div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Reason Card 1 -->
        <div class="glassmorphism p-8 rounded-2xl text-center border-luxuryGold/10 hover:-translate-y-3 transition-transform duration-500 flex flex-col items-center">
          <div class="w-16 h-16 rounded-full bg-pink-500/10 border border-pink-500/30 flex items-center justify-center text-romanticPink text-2xl mb-6 shadow-inner animate-pulse">
            <i class="fas fa-smile-beam"></i>
          </div>
          <h3 class="text-xl font-bold text-white mb-3">Your Beautiful Smile</h3>
          <p class="text-sm leading-relaxed text-pink-100/70">
            Your smile holds a magical warmth that instantly melts away any sorrow. It is the sunrise that brightens my darkest of days mela bacchaaa.
          </p>
        </div>

        <!-- Reason Card 2 -->
        <div class="glassmorphism p-8 rounded-2xl text-center border-luxuryGold/10 hover:-translate-y-3 transition-transform duration-500 flex flex-col items-center">
          <div class="w-16 h-16 rounded-full bg-luxuryGold/10 border border-luxuryGold/30 flex items-center justify-center text-luxuryGold text-2xl mb-6 shadow-inner animate-pulse">
            <i class="fas fa-hand-holding-heart"></i>
          </div>
          <h3 class="text-xl font-bold text-white mb-3">Your Gentle Kind Heart</h3>
          <p class="text-sm leading-relaxed text-pink-100/70">
            The pure, unconditional empathy you radiate with everything you touch. You inspire me to be a better person just by being close to you mela bacchaaa.
          </p>
        </div>

        <!-- Reason Card 3 -->
        <div class="glassmorphism p-8 rounded-2xl text-center border-luxuryGold/10 hover:-translate-y-3 transition-transform duration-500 flex flex-col items-center">
          <div class="w-16 h-16 rounded-full bg-pink-500/10 border border-pink-500/30 flex items-center justify-center text-glowingRed text-2xl mb-6 shadow-inner animate-pulse">
            <i class="fas fa-infinity"></i>
          </div>
          <h3 class="text-xl font-bold text-white mb-3">Your Soul's Guidance</h3>
          <p class="text-sm leading-relaxed text-pink-100/70">
            You are my rock, my true north, and my compass. With your hand resting in mine, there is absolutely no storm we cannot conquer mela bacchaaa.
          </p>
        </div>
      </div>
    </section>

    <!-- SECTION 3: My Heart Speaks Mela Bacchaaa-->
    <section class="py-24 relative">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-6xl font-cursive text-luxuryGold">My Heart Speaks</h2>
        <div class="h-[1px] w-40 bg-gradient-to-r from-transparent via-luxuryGold to-transparent mx-auto mt-2"></div>
      </div>

      <div class="glassmorphism p-8 md:p-12 rounded-3xl max-w-4xl mx-auto border-pink-400/10 shadow-2xl relative min-h-[350px] flex items-center">
        <!-- Floating overlay design elements -->
        <div class="absolute -top-4 -left-4 w-12 h-12 border-t-2 border-l-2 border-luxuryGold/40 rounded-tl-xl"></div>
        <div class="absolute -bottom-4 -right-4 w-12 h-12 border-b-2 border-r-2 border-luxuryGold/40 rounded-br-xl"></div>
        
        <div class="w-full">
          <i class="fas fa-quote-left text-4xl text-luxuryGold/30 mb-4 block"></i>
          <!-- Container for triggering scroll typing animation -->
          <div id="typewriterTarget" class="font-cursive text-2xl md:text-4xl text-pink-100 leading-relaxed text-center min-h-[160px] md:min-h-[220px]">
            <!-- JavaScript will insert the premium slow typewriter letters here -->
          </div>
          <div class="text-right mt-6">
            <span class="font-cursive text-2xl text-luxuryGold font-bold">- Yours Forever, Husband Meli Pyali Patni Jii</span>
          </div>
        </div>
      </div>
    </section>

    <!-- SECTION 4: Memory Gallery -->
    <section class="py-24 relative">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-6xl font-cursive text-luxuryGold">Memory Gallery</h2>
        <p class="text-pink-300/70 text-sm uppercase tracking-wider mt-2">Capturing timeless moments of us (tap to hover)</p>
        <div class="h-[1px] w-40 bg-gradient-to-r from-transparent via-luxuryGold to-transparent mx-auto mt-2"></div>
      </div>

      <!-- Scattered Polaroid Grid -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-12 max-w-5xl mx-auto py-8">
        
        <!-- Polaroid 1 -->
        <div class="polaroid mx-auto" style="--rotation: -5deg;">
          <div class="bg-gray-100 w-full h-56 rounded-md overflow-hidden flex items-center justify-center border border-gray-200 relative group">
            <!-- Simulated image placeholder with custom SVG/Icon -->
            <img src="https://raw.githubusercontent.com/amansonwani943/For-Meli-Pyali-Patni-Jii-/main/IMG_20260714_234910.jpg"
     alt="Our Beautiful Moments Together"
     class="w-full h-full object-cover rounded-md">
          </div>
          <div class="text-center font-cursive text-2xl text-[#310411] mt-4 font-bold">Unending Joy</div>
        </div>

        <!-- Polaroid 2 -->
        <div class="polaroid mx-auto" style="--rotation: 3deg;">
          <div class="bg-gray-100 w-full h-56 rounded-md overflow-hidden flex items-center justify-center border border-gray-200 relative group">
            <div class="absolute inset-0 bg-gradient-to-br from-purple-400/20 to-roseGold/30 flex flex-col items-center justify-center text-pink-500/60 p-4">
              <i class="fas fa-heart text-4xl mb-2"></i>
              <span class="text-[10px] text-gray-500 uppercase tracking-widest font-semibold text-center">Add Sweet Vacation Photo Here</span>
            </div>
          </div>
          <div class="text-center font-cursive text-2xl text-[#310411] mt-4 font-bold">First Date</div>
        </div>

        <!-- Polaroid 3 -->
        <div class="polaroid mx-auto" style="--rotation: -3deg;">
          <div class="bg-gray-100 w-full h-56 rounded-md overflow-hidden flex items-center justify-center border border-gray-200 relative group">
            <div class="absolute inset-0 bg-gradient-to-br from-yellow-300/20 to-pink-500/30 flex flex-col items-center justify-center text-pink-500/60 p-4">
              <i class="fas fa-camera text-4xl mb-2"></i>
              <span class="text-[10px] text-gray-500 uppercase tracking-widest font-semibold text-center">Add Sweet Dinner Photo Here</span>
            </div>
          </div>
          <div class="text-center font-cursive text-2xl text-[#310411] mt-4 font-bold">Warm Hugs</div>
        </div>

        <!-- Polaroid 4 -->
        <div class="polaroid mx-auto" style="--rotation: 6deg;">
          <div class="bg-gray-100 w-full h-56 rounded-md overflow-hidden flex items-center justify-center border border-gray-200 relative group">
            <div class="absolute inset-0 bg-gradient-to-br from-[#a11b3c]/20 to-indigo-500/30 flex flex-col items-center justify-center text-pink-500/60 p-4">
              <i class="fas fa-glass-cheers text-4xl mb-2"></i>
              <span class="text-[10px] text-gray-500 uppercase tracking-widest font-semibold text-center">Add Anniversary Photo Here</span>
            </div>
          </div>
          <div class="text-center font-cursive text-2xl text-[#310411] mt-4 font-bold">Our Anniversary mela pyali patni jii</div>
        </div>

      </div>
    </section>

    <!-- SECTION 5: Love Counter -->
    <section class="py-24 relative">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-6xl font-cursive text-luxuryGold">Love Counter</h2>
        <p class="text-pink-300/70 text-sm uppercase tracking-wider mt-2">Every millisecond spent with you is a treasure</p>
        <div class="h-[1px] w-40 bg-gradient-to-r from-transparent via-luxuryGold to-transparent mx-auto mt-2"></div>
      </div>

      <!-- Luxury Counter Display -->
      <div class="grid grid-cols-2 md:grid-cols-4 gap-6 max-w-4xl mx-auto text-center">
        <!-- Days Card mela bacchaa-->
        <div class="glassmorphism p-6 rounded-2xl border-luxuryGold/10 relative overflow-hidden group">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-luxuryGold to-pink-500"></div>
          <div id="counterDays" class="text-4xl md:text-5xl font-bold font-poppins text-luxuryGold mb-2 tracking-tight">00</div>
          <div class="text-xs tracking-widest text-pink-200 uppercase font-semibold">Days Together</div>
        </div>

        <!-- Hours Card mela bacchaaa-->
        <div class="glassmorphism p-6 rounded-2xl border-luxuryGold/10 relative overflow-hidden group">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-luxuryGold to-pink-500"></div>
          <div id="counterHours" class="text-4xl md:text-5xl font-bold font-poppins text-luxuryGold mb-2 tracking-tight">00</div>
          <div class="text-xs tracking-widest text-pink-200 uppercase font-semibold">Hours</div>
        </div>

        <!-- Minutes Card mela bacchaa-->
        <div class="glassmorphism p-6 rounded-2xl border-luxuryGold/10 relative overflow-hidden group">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-luxuryGold to-pink-500"></div>
          <div id="counterMinutes" class="text-4xl md:text-5xl font-bold font-poppins text-luxuryGold mb-2 tracking-tight">00</div>
          <div class="text-xs tracking-widest text-pink-200 uppercase font-semibold">Minutes</div>
        </div>

        <!-- Seconds Card mela bacchaa-->
        <div class="glassmorphism p-6 rounded-2xl border-luxuryGold/10 relative overflow-hidden group">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-luxuryGold to-pink-500"></div>
          <div id="counterSeconds" class="text-4xl md:text-5xl font-bold font-poppins text-glowingRed mb-2 tracking-tight animate-pulse">00</div>
          <div class="text-xs tracking-widest text-pink-200 uppercase font-semibold">Seconds</div>
        </div>
      </div>
    </section>

    <!-- SECTION 6: Love Letter Envelope Mela Bacchaaa-->
    <section class="py-24 relative flex flex-col items-center">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-6xl font-cursive text-luxuryGold">Love Letter</h2>
        <p class="text-pink-300/70 text-sm uppercase tracking-wider mt-2">Tap to open the sealed letter inside my heart mela bacchaa</p>
        <div class="h-[1px] w-40 bg-gradient-to-r from-transparent via-luxuryGold to-transparent mx-auto mt-2"></div>
      </div>

      <!-- 3D Envelope Container Wrapper -->
      <div id="interactiveEnvelope" class="envelope-wrapper mb-24">
        <div class="envelope">
          <div class="flap-top"></div>
          <div class="flap-sides"></div>
          <div class="flap-bottom"></div>
          
          <!-- Inner letter paper card structure -->
          <div class="letter-card scroll-smooth">
            <h4 class="font-cursive text-3xl font-bold text-[#7a0928] mb-4 text-center">My Beautiful Wife,</h4>
            <div class="space-y-4 font-poppins text-xs md:text-sm text-pink-950 font-medium leading-relaxed">
              <p>
                From the second I married you, my definition of true happiness transformed. You are my light, my calm, and my most beautiful blessing mela bacchaa.
              </p>
              <p>
                Every smile of yours gives complete meaning to my world. No matter how challenging life's path becomes, I promise to stand by you, shielding you and loving you with every fiber of my soul meli pyali ardhangini jii .
              </p>
              <p>
                You are my forever home, and I love you beyond words. Thank you for choosing to walk this life with me meli pyali patni jii.
              </p>
            </div>
            <div class="text-right mt-6 font-cursive text-2xl text-[#7a0928] font-bold">
              Aapke Pyare Pati Jii❤️
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- SECTION 7: Promise Cards Mela Bacchaa-->
    <section class="py-24 relative">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-6xl font-cursive text-luxuryGold">My Sacred Promises</h2>
        <p class="text-pink-300/70 text-sm uppercase tracking-wider mt-2">Promises carved in stone, dedicated forever to you</p>
        <div class="h-[1px] w-40 bg-gradient-to-r from-transparent via-luxuryGold to-transparent mx-auto mt-2"></div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-4 gap-6 max-w-5xl mx-auto">
        <!-- Promise Card 1 -->
        <div class="promise-card w-full h-64 perspective-1000">
          <div class="promise-card-inner relative w-full h-full text-center">
            <!-- Front side -->
            <div class="promise-front glassmorphism p-6 flex flex-col justify-center items-center border-pink-400/10">
              <i class="fas fa-shield-alt text-4xl text-luxuryGold mb-4"></i>
              <h3 class="text-lg font-bold text-pink-200">Protection</h3>
              <p class="text-xs text-white/50 mt-2">Hover to flip</p>
            </div>
            <!-- Back side -->
            <div class="promise-back bg-gradient-to-br from-deepVelvet to-black p-6 flex flex-col justify-center items-center border border-luxuryGold/40">
              <h3 class="text-xl font-bold font-cursive text-luxuryGold mb-2">My Promise</h3>
              <p class="text-sm text-pink-100/90 leading-relaxed">
                "I will always protect your dreams, your smile, and your beautiful heart from any shadow meli pyali ardhangini jii."
              </p>
            </div>
          </div>
        </div>

        <!-- Promise Card 2 Mela Bacchaa-->
        <div class="promise-card w-full h-64 perspective-1000">
          <div class="promise-card-inner relative w-full h-full text-center">
            <!-- Front side -->
            <div class="promise-front glassmorphism p-6 flex flex-col justify-center items-center border-pink-400/10">
              <i class="fas fa-hands-helping text-4xl text-luxuryGold mb-4"></i>
              <h3 class="text-lg font-bold text-pink-200">Respect</h3>
              <p class="text-xs text-white/50 mt-2">Hover to flip</p>
            </div>
            <!-- Back side -->
            <div class="promise-back bg-gradient-to-br from-deepVelvet to-black p-6 flex flex-col justify-center items-center border border-luxuryGold/40">
              <h3 class="text-xl font-bold font-cursive text-luxuryGold mb-2">My Promise Mela Bacchaa</h3>
              <p class="text-sm text-pink-100/90 leading-relaxed">
                "I will always treat you with utmost dignity, honoring your beautiful intelligence and unique spirit mela bacchaa."
              </p>
            </div>
          </div>
        </div>

        <!-- Promise Card 3 Mela Bacchaa-->
        <div class="promise-card w-full h-64 perspective-1000">
          <div class="promise-card-inner relative w-full h-full text-center">
            <!-- Front side -->
            <div class="promise-front glassmorphism p-6 flex flex-col justify-center items-center border-pink-400/10">
              <i class="fas fa-check-circle text-4xl text-luxuryGold mb-4"></i>
              <h3 class="text-lg font-bold text-pink-200">Devotion</h3>
              <p class="text-xs text-white/50 mt-2">Hover to flip</p>
            </div>
            <!-- Back side -->
            <div class="promise-back bg-gradient-to-br from-deepVelvet to-black p-6 flex flex-col justify-center items-center border border-luxuryGold/40">
              <h3 class="text-xl font-bold font-cursive text-luxuryGold mb-2">My Promise</h3>
              <p class="text-sm text-pink-100/90 leading-relaxed">
                "Every single morning, day after day, year after year, I will choose you over and over again meli pyali biwi jii."
              </p>
            </div>
          </div>
        </div>

        <!-- Promise Card 4 Mela Bacchaaa->
        <div class="promise-card w-full h-64 perspective-1000">
          <div class="promise-card-inner relative w-full h-full text-center">
            <!-- Front side -->
            <div class="promise-front glassmorphism p-6 flex flex-col justify-center items-center border-pink-400/10">
              <i class="fas fa-infinity text-4xl text-luxuryGold mb-4"></i>
              <h3 class="text-lg font-bold text-pink-200">Eternity</h3>
              <p class="text-xs text-white/50 mt-2">Hover to flip</p>
            </div>
            <!-- Back side -->
            <div class="promise-back bg-gradient-to-br from-deepVelvet to-black p-6 flex flex-col justify-center items-center border border-luxuryGold/40">
              <h3 class="text-xl font-bold font-cursive text-luxuryGold mb-2">My Promise</h3>
              <p class="text-sm text-pink-100/90 leading-relaxed">
                "My soul's devotion to you does not end with this physical life. I will love you beyond forever meli pyali patni jii."
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- SECTION 8: Final Epic Glowing Interactive Heart & Proposal Question Mela Bacchaa-->
    <section class="py-24 relative flex flex-col items-center">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-6xl font-cursive text-luxuryGold">My Heart Awaits You</h2>
        <p class="text-pink-300/70 text-sm uppercase tracking-wider mt-2">Tap the sacred 3D heart below to see my soul explode</p>
        <div class="h-[1px] w-40 bg-gradient-to-r from-transparent via-luxuryGold to-transparent mx-auto mt-2"></div>
      </div>

      <!-- Glowing Heart Wrapper -->
      <div class="relative cursor-pointer flex justify-center items-center select-none w-72 h-72 mb-12">
        <!-- SVG 3D-feeling pulsing glassmorphism glowing heart -->
        <svg id="interactiveHeart" class="w-64 h-64 animate-pulse-glow transition-all duration-300 transform active:scale-90" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="heartGradient" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#FF0055" />
              <stop offset="40%" stop-color="#FF5E62" />
              <stop offset="100%" stop-color="#D4AF37" />
            </linearGradient>
            <filter id="glowEffect" x="-20%" y="-20%" width="140%" height="140%">
              <feGaussianBlur stdDeviation="3" result="blur" />
              <feComposite in="SourceGraphic" in2="blur" operator="over" />
            </filter>
          </defs>
          <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z" fill="url(#heartGradient)" filter="url(#glowEffect)" />
        </svg>
      </div>

      <div class="text-center max-w-xl px-4">
        <h3 class="text-4xl md:text-5xl font-cursive text-luxuryGold mb-8">I Love You Forever Meli Pyali Ardhangini Jii ❤️</h3>
        
        <!-- Big Final Interactive Question Button Mela Bacchaaa-->
        <button id="proposalBtn" class="group relative px-10 py-5 bg-gradient-to-r from-glowingRed via-pink-500 to-luxuryGold font-extrabold text-sm uppercase tracking-widest text-white rounded-full shadow-[0_10px_40px_rgba(255,0,85,0.4)] hover:shadow-[0_15px_50px_rgba(255,0,85,0.7)] border-2 border-white/20 transition-all duration-300 overflow-hidden active:scale-95">
          <span class="relative z-10">Will You Stay With Me Forever?</span>
          <!-- Glitter hover background effect -->
          <span class="absolute inset-0 bg-gradient-to-r from-luxuryGold via-pink-400 to-glowingRed opacity-0 group-hover:opacity-100 transition-opacity duration-500"></span>
        </button>
      </div>
    </section>
  </main>

  <!-- STEP 3: Complete Celebration Overlay Screen (Yes Response) -->
  <div id="celebrationOverlay" class="fixed inset-0 z-50 bg-black/95 backdrop-blur-2xl flex flex-col justify-center items-center text-center px-6 hidden opacity-0 transition-opacity duration-1000">
    <!-- Huge golden dynamic crown / wedding heart inside glowing particles -->
    <div class="relative mb-10 w-44 h-44 flex items-center justify-center">
      <i class="fas fa-heart text-glowingRed text-9xl animate-ping absolute opacity-30"></i>
      <i class="fas fa-ring text-luxuryGold text-7xl absolute animate-bounce"></i>
      <i class="fas fa-heart text-romanticPink text-5xl relative z-10"></i>
    </div>

    <h1 class="text-5xl md:text-8xl font-cursive text-luxuryGold shimmer-text font-bold mb-6">
      Thank You, Meli Pyali Patni Jii!
    </h1>
    
    <p class="text-lg md:text-2xl text-pink-100 max-w-2xl font-light italic leading-relaxed">
      "Our hearts are forever bound, stronger than time itself. I promise to cherish every second of this life making you the happiest woman alive mela pyala baccchaaa."
    </p>

    <!-- Close button for letting wife explore the site again -->
    <button id="closeOverlayBtn" class="mt-12 bg-white/10 hover:bg-white/20 text-white/90 border border-white/20 py-2.5 px-8 rounded-full text-xs uppercase tracking-widest transition-all">
      Return to Our Memories Mela Pyala Bacchaaa
    </button>
  </div>

  <script>
    /* ==========================================================================
       ROBUST SYNTH AUDIO ENGINE
       Procedural Music Box Synthesizer (Zero URLs, Web Audio API)
       ========================================================================== */
    class RomanticMusicEngine {
      constructor() {
        this.ctx = null;
        this.isPlaying = false;
        this.notes = [261.63, 293.66, 329.63, 349.23, 392.00, 440.00, 493.88, 523.25]; // C major scale
        this.progression = [
          [329.63, 392.00, 523.25], // C major triad
          [349.23, 440.00, 523.25], // F major triad
          [392.00, 493.88, 587.33], // G major triad
          [261.63, 329.63, 392.00], // C major triad home
        ];
        this.currentStep = 0;
        this.intervalId = null;
      }

      init() {
        try {
          const AudioContextClass = window.AudioContext || window.webkitAudioContext;
          this.ctx = new AudioContextClass();
        } catch (e) {
          console.warn("Web Audio API is not supported in this browser environment.", e);
        }
      }

      start() {
        if (!this.ctx) this.init();
        if (this.isPlaying) return;

        // Resume Audio Context in case of browser locking auto-play
        if (this.ctx.state === 'suspended') {
          this.ctx.resume();
        }

        this.isPlaying = true;
        this.currentStep = 0;
        this.playPattern();
        
        // Loop the beautiful lullaby melody
        this.intervalId = setInterval(() => {
          this.playPattern();
        }, 1800);
      }

      stop() {
        this.isPlaying = false;
        if (this.intervalId) {
          clearInterval(this.intervalId);
          this.intervalId = null;
        }
      }

      // Simple procedural warm synth voice
      playPattern() {
        if (!this.ctx || !this.isPlaying) return;
        const now = this.ctx.currentTime;
        const chords = this.progression[this.currentStep % this.progression.length];

        // 1. Play Soft Pad Chord Voice (Low filter frequency warmth)
        chords.forEach((note, index) => {
          this.createSynthVoice(note / 2, now, 1.4, 0.04);
        });

        // 2. Play High Ambient Bell Melody (Music box sound)
        const melodyOffset = [0, 0.3, 0.6, 0.9, 1.2];
        melodyOffset.forEach((offsetTime, index) => {
          // Select a romantic sweet note from current chord scale
          const chordNote = chords[index % chords.length];
          const octMelody = chordNote * 2; 
          this.createBellVoice(octMelody, now + offsetTime, 0.5, 0.06);
        });

        this.currentStep++;
      }

      createSynthVoice(freq, startTime, duration, volume) {
        const osc = this.ctx.createOscillator();
        const gainNode = this.ctx.createGain();
        const filter = this.ctx.createBiquadFilter();

        osc.type = 'triangle';
        osc.frequency.setValueAtTime(freq, startTime);

        filter.type = 'lowpass';
        filter.frequency.setValueAtTime(400, startTime);

        gainNode.gain.setValueAtTime(0, startTime);
        gainNode.gain.linearRampToValueAtTime(volume, startTime + 0.3);
        gainNode.gain.exponentialRampToValueAtTime(0.0001, startTime + duration);

        osc.connect(filter);
        filter.connect(gainNode);
        gainNode.connect(this.ctx.destination);

        osc.start(startTime);
        osc.stop(startTime + duration);
      }

      createBellVoice(freq, startTime, duration, volume) {
        const osc = this.ctx.createOscillator();
        const gainNode = this.ctx.createGain();

        // Music Box Bell-like clean tone
        osc.type = 'sine';
        osc.frequency.setValueAtTime(freq, startTime);

        gainNode.gain.setValueAtTime(0, startTime);
        gainNode.gain.linearRampToValueAtTime(volume, startTime + 0.05);
        gainNode.gain.exponentialRampToValueAtTime(0.0001, startTime + duration);

        osc.connect(gainNode);
        gainNode.connect(this.ctx.destination);

        osc.start(startTime);
        osc.stop(startTime + duration);
      }
    }

    const synth = new RomanticMusicEngine();

    // Configure Audio Unmute Action Controller
    const musicToggleBtn = document.getElementById('musicToggleBtn');
    const musicIcon = document.getElementById('musicIcon');
    const musicToast = document.getElementById('musicToast');

    function showAudioToast(text) {
      musicToast.innerText = text;
      musicToast.classList.remove('hidden');
      setTimeout(() => musicToast.classList.add('opacity-100'), 50);
      setTimeout(() => {
        musicToast.classList.remove('opacity-100');
        setTimeout(() => musicToast.classList.add('hidden'), 300);
      }, 2500);
    }

    musicToggleBtn.addEventListener('click', () => {
      if (synth.isPlaying) {
        synth.stop();
        musicIcon.className = 'fas fa-volume-mute text-lg';
        showAudioToast("🔇 Music Muted");
      } else {
        synth.start();
        musicIcon.className = 'fas fa-volume-up text-lg text-luxuryGold animate-bounce';
        showAudioToast("🎶 Play Romantic Melodies");
      }
    });

    /* ==========================================================================
       DOUBLE CANVAS ANIMATION LAYER
       Ambient Starry Sky + Floating Hearts & Rose Petals & Celebration Fireworks
       ========================================================================== */
    const ambientCanvas = document.getElementById('ambientCanvas');
    const ambientCtx = ambientCanvas.getContext('2d');

    const celebrationCanvas = document.getElementById('celebrationCanvas');
    const celebrationCtx = celebrationCanvas.getContext('2d');

    let screenWidth = window.innerWidth;
    let screenHeight = window.innerHeight;

    function resizeCanvases() {
      screenWidth = window.innerWidth;
      screenHeight = window.innerHeight;
      
      ambientCanvas.width = screenWidth;
      ambientCanvas.height = screenHeight;
      
      celebrationCanvas.width = screenWidth;
      celebrationCanvas.height = screenHeight;
    }
    window.addEventListener('resize', resizeCanvases);
    resizeCanvases();

    // Ambient Star, Hearts and Rose Petal Entities
    const ambientParticles = [];
    const stars = [];

    // Construct stars backdrops
    for (let i = 0; i < 100; i++) {
      stars.push({
        x: Math.random() * screenWidth,
        y: Math.random() * screenHeight,
        radius: Math.random() * 1.5,
        alpha: Math.random(),
        speed: 0.01 + Math.random() * 0.02
      });
    }

    class FloatingEntity {
      constructor() {
        this.reset();
      }

      reset() {
        this.x = Math.random() * screenWidth;
        this.y = screenHeight + 50;
        this.type = Math.random() > 0.5 ? 'heart' : 'petal';
        this.size = 8 + Math.random() * 14;
        this.speedY = 0.5 + Math.random() * 1.2;
        this.speedX = -0.5 + Math.random() * 1;
        this.rotation = Math.random() * Math.PI * 2;
        this.rotationSpeed = -0.01 + Math.random() * 0.02;
        this.alpha = 0.3 + Math.random() * 0.5;
        this.color = this.type === 'heart' 
          ? `hsla(${340 + Math.random() * 20}, 100%, 70%, ${this.alpha})`
          : `hsla(${350 + Math.random() * 15}, 90%, 60%, ${this.alpha})`;
      }

      update() {
        this.y -= this.speedY;
        this.x += this.speedX;
        this.rotation += this.rotationSpeed;
        if (this.y < -50 || this.x < -50 || this.x > screenWidth + 50) {
          this.reset();
        }
      }

      draw(ctx) {
        ctx.save();
        ctx.translate(this.x, this.y);
        ctx.rotate(this.rotation);
        ctx.fillStyle = this.color;

        if (this.type === 'heart') {
          // Beautiful Vector drawing of heart
          ctx.beginPath();
          ctx.moveTo(0, 0);
          ctx.bezierCurveTo(-this.size / 2, -this.size / 2, -this.size, -this.size / 3, -this.size, this.size / 4);
          ctx.bezierCurveTo(-this.size, this.size, 0, this.size * 1.5, 0, this.size * 1.8);
          ctx.bezierCurveTo(0, this.size * 1.5, this.size, this.size, this.size, this.size / 4);
          ctx.bezierCurveTo(this.size, -this.size / 3, this.size / 2, -this.size / 2, 0, 0);
          ctx.closePath();
          ctx.fill();
        } else {
          // Drawing Organic Rose Petals
          ctx.beginPath();
          ctx.ellipse(0, 0, this.size * 0.7, this.size, 0, 0, Math.PI * 2);
          ctx.closePath();
          ctx.fill();
        }
        ctx.restore();
      }
    }

    // Load initial ambient rising objects
    for (let i = 0; i < 40; i++) {
      ambientParticles.push(new FloatingEntity());
    }

    /* High Performance Interactive Fireworks System */
    const fireworks = [];
    const celebrationParticles = [];

    class Firework {
      constructor(targetX, targetY) {
        this.x = Math.random() * screenWidth;
        this.y = screenHeight;
        this.targetX = targetX;
        this.targetY = targetY;
        this.speed = 4 + Math.random() * 4;
        this.angle = Math.atan2(targetY - this.y, targetX - this.x);
        this.vx = Math.cos(this.angle) * this.speed;
        this.vy = Math.sin(this.angle) * this.speed;
        this.exploded = false;
        this.hue = Math.random() * 360;
      }

      update() {
        this.x += this.vx;
        this.y += this.vy;
        
        // Distance check to explode
        const distToTarget = Math.hypot(this.targetX - this.x, this.targetY - this.y);
        if (distToTarget < 15 || this.y < this.targetY + 10) {
          this.exploded = true;
          this.explode();
        }
      }

      explode() {
        const pCount = 80;
        for (let i = 0; i < pCount; i++) {
          const angle = (i / pCount) * Math.PI * 2 + (Math.random() * 0.5);
          const velocity = 2 + Math.random() * 5;
          celebrationParticles.push(new CelebrationParticle(
            this.targetX, 
            this.targetY, 
            Math.cos(angle) * velocity, 
            Math.sin(angle) * velocity,
            this.hue
          ));
        }
      }

      draw(ctx) {
        if (this.exploded) return;
        ctx.beginPath();
        ctx.arc(this.x, this.y, 3, 0, Math.PI * 2);
        ctx.fillStyle = `hsl(${this.hue}, 100%, 75%)`;
        ctx.shadowBlur = 10;
        ctx.shadowColor = `hsl(${this.hue}, 100%, 75%)`;
        ctx.fill();
        ctx.shadowBlur = 0;
      }
    }

    class CelebrationParticle {
      constructor(x, y, vx, vy, hue) {
        this.x = x;
        this.y = y;
        this.vx = vx;
        this.vy = vy;
        this.alpha = 1.0;
        this.decay = 0.01 + Math.random() * 0.015;
        this.hue = hue;
        this.isHeart = Math.random() > 0.4;
        this.size = 2 + Math.random() * 4;
      }

      update() {
        this.x += this.vx;
        this.y += this.vy;
        this.vy += 0.04; // gravity simulation
        this.alpha -= this.decay;
      }

      draw(ctx) {
        ctx.save();
        ctx.globalAlpha = this.alpha;
        ctx.translate(this.x, this.y);
        ctx.fillStyle = `hsl(${this.hue}, 100%, 65%)`;
        ctx.shadowBlur = 5;
        ctx.shadowColor = `hsl(${this.hue}, 100%, 65%)`;

        if (this.isHeart) {
          ctx.beginPath();
          ctx.moveTo(0, 0);
          ctx.bezierCurveTo(-this.size, -this.size, -this.size * 2, -this.size, -this.size * 2, 0);
          ctx.bezierCurveTo(-this.size * 2, this.size * 1.5, 0, this.size * 2.5, 0, this.size * 3);
          ctx.bezierCurveTo(0, this.size * 2.5, this.size * 2, this.size * 1.5, this.size * 2, 0);
          ctx.bezierCurveTo(this.size * 2, -this.size, this.size, -this.size, 0, 0);
          ctx.closePath();
          ctx.fill();
        } else {
          ctx.beginPath();
          ctx.arc(0, 0, this.size, 0, Math.PI * 2);
          ctx.fill();
        }
        ctx.restore();
      }
    }

    // Master Animation Loop
    function animationLoop() {
      // 1. Draw Background Stars & ambient rising hearts
      ambientCtx.clearRect(0, 0, screenWidth, screenHeight);
      
      // Draw Stars
      stars.forEach(star => {
        star.alpha += star.speed;
        if (star.alpha > 1 || star.alpha < 0) star.speed = -star.speed;
        ambientCtx.beginPath();
        ambientCtx.arc(star.x, star.y, star.radius, 0, Math.PI * 2);
        ambientCtx.fillStyle = `rgba(255, 255, 255, ${Math.max(0, star.alpha)})`;
        ambientCtx.fill();
      });

      // Update & Draw Ambient items
      ambientParticles.forEach(p => {
        p.update();
        p.draw(ambientCtx);
      });

      // 2. Clear Celebration Canvas
      celebrationCtx.clearRect(0, 0, screenWidth, screenHeight);

      // Handle Fireworks logic
      for (let i = fireworks.length - 1; i >= 0; i--) {
        fireworks[i].update();
        fireworks[i].draw(celebrationCtx);
        if (fireworks[i].exploded) {
          fireworks.splice(i, 1);
        }
      }

      // Handle fireworks explosive sparks
      for (let i = celebrationParticles.length - 1; i >= 0; i--) {
        celebrationParticles[i].update();
        celebrationParticles[i].draw(celebrationCtx);
        if (celebrationParticles[i].alpha <= 0) {
          celebrationParticles.splice(i, 1);
        }
      }

      requestAnimationFrame(animationLoop);
    }
    requestAnimationFrame(animationLoop);

    /* ==========================================================================
       Surprise Trigger & Landing Flow Control
       ========================================================================== */
    const landingScreen = document.getElementById('landingScreen');
    const mainContent = document.getElementById('mainContent');
    const giftWrapper = document.getElementById('giftWrapper');
    const boxLoader = document.getElementById('boxLoader');
    const interactiveGiftContainer = document.getElementById('interactiveGiftContainer');
    const giftOpenBtn = document.getElementById('giftOpenBtn');

    // Simulate 2 seconds of deep high-end magic pre-loading
    setTimeout(() => {
      boxLoader.classList.add('hidden');
      giftWrapper.classList.remove('hidden');
    }, 2000);

    function triggerSurpriseExplosion() {
      // Avoid multi tap activation triggers
      if (interactiveGiftContainer.classList.contains('gift-opened')) return;

      interactiveGiftContainer.classList.add('gift-opened');
      
      // Auto-trigger synthetic music logic
      synth.start();
      musicIcon.className = 'fas fa-volume-up text-lg text-luxuryGold animate-bounce';
      
      // Trigger instant premium fireworks bursts
      for (let i = 0; i < 15; i++) {
        setTimeout(() => {
          const randX = Math.random() * screenWidth;
          const randY = 100 + Math.random() * (screenHeight - 300);
          fireworks.push(new Firework(randX, randY));
        }, i * 150);
      }

      // Transition landing layout screens
      setTimeout(() => {
        landingScreen.classList.add('opacity-0');
        mainContent.classList.remove('hidden');
        setTimeout(() => {
          landingScreen.classList.add('hidden');
          mainContent.classList.remove('opacity-0');
          // Trigger Love Counter and observers on entrance
          initLoveCounter();
        }, 1000);
      }, 1500);
    }

    interactiveGiftContainer.addEventListener('click', triggerSurpriseExplosion);
    giftOpenBtn.addEventListener('click', triggerSurpriseExplosion);

    /* ==========================================================================
       Interactive Typewriter Script Logic
       ========================================================================== */
    const emotionalText = "Mela pyala baccchaa, \nYou are the most beautiful blessing of my life. \nEvery smile of yours gives meaning to my world mela bacchaa. \nNo matter how difficult life becomes bubuuu, I promise to stand beside you forever mela bacchaa. \nYou are my happiness meli pyali patni jii, my peace, my forever home mela chota sa bacchaa. \nI love you more than words can ever express mela bacchaa.";
    
    let typewriterStarted = false;

    function runTypewriter() {
      if (typewriterStarted) return;
      typewriterStarted = true;
      const target = document.getElementById('typewriterTarget');
      let index = 0;
      target.innerHTML = '';

      function type() {
        if (index < emotionalText.length) {
          const char = emotionalText.charAt(index);
          if (char === '\n') {
            target.innerHTML += '<br>';
          } else {
            target.innerHTML += char;
          }
          index++;
          setTimeout(type, 45); // highly legible cinematic typing interval speed
        }
      }
      type();
    }

    // Trigger Typewriter only when visible
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          runTypewriter();
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.4 });

    observer.observe(document.getElementById('typewriterTarget'));

    /* ==========================================================================
       3D Love Letter Envelope Click Handler
       ========================================================================== */
    const interactiveEnvelope = document.getElementById('interactiveEnvelope');
    interactiveEnvelope.addEventListener('click', (e) => {
      // Prevent child elements scrolling from re-triggering closures
      if (e.target.closest('.letter-card') && interactiveEnvelope.classList.contains('open')) {
        return;
      }
      interactiveEnvelope.classList.toggle('open');
    });

    /* ==========================================================================
       Precise Love Counter System (Adjust date as needed)
       ========================================================================== */
    // Change this date string to your actual anniversary date! (Year, Month Index 0-11, Day)
    const anniversaryDate = new Date('2024-06-19T00:00:00');

    function updateCounters() {
      const now = new Date();
      const diffMs = now - anniversaryDate;

      const diffSecs = Math.floor(diffMs / 1000);
      const days = Math.floor(diffSecs / (24 * 3600));
      const hours = Math.floor((diffSecs % (24 * 3600)) / 3600);
      const mins = Math.floor((diffSecs % 3600) / 60);
      const secs = diffSecs % 60;

      document.getElementById('counterDays').innerText = String(days).padStart(2, '0');
      document.getElementById('counterHours').innerText = String(hours).padStart(2, '0');
      document.getElementById('counterMinutes').innerText = String(mins).padStart(2, '0');
      document.getElementById('counterSeconds').innerText = String(secs).padStart(2, '0');
    }

    function initLoveCounter() {
      updateCounters();
      setInterval(updateCounters, 1000);
    }

    /* ==========================================================================
       Glowing Interactive 3D Heart Click Handler
       ========================================================================== */
    const interactiveHeart = document.getElementById('interactiveHeart');
    interactiveHeart.addEventListener('click', () => {
      // Visual feedback tap scale
      interactiveHeart.classList.add('scale-75');
      setTimeout(() => {
        interactiveHeart.classList.remove('scale-75');
      }, 150);

      // Instantly generate 6 beautiful overlapping fireworks
      for (let i = 0; i < 6; i++) {
        setTimeout(() => {
          const targetX = screenWidth * 0.15 + (Math.random() * (screenWidth * 0.7));
          const targetY = screenHeight * 0.1 + (Math.random() * (screenHeight * 0.4));
          fireworks.push(new Firework(targetX, targetY));
        }, i * 180);
      }
    });

    /* ==========================================================================
       Epic Final Proposal Celebration Trigger
       ========================================================================== */
    const proposalBtn = document.getElementById('proposalBtn');
    const celebrationOverlay = document.getElementById('celebrationOverlay');
    const closeOverlayBtn = document.getElementById('closeOverlayBtn');

    proposalBtn.addEventListener('click', () => {
      // Trigger mass celebration explosions
      for (let i = 0; i < 35; i++) {
        setTimeout(() => {
          const randX = Math.random() * screenWidth;
          const randY = 100 + Math.random() * (screenHeight - 300);
          fireworks.push(new Firework(randX, randY));
        }, i * 100);
      }

      // Fade-in full-screen emotional celebration overlay
      celebrationOverlay.classList.remove('hidden');
      setTimeout(() => {
        celebrationOverlay.classList.remove('opacity-0');
        celebrationOverlay.classList.add('opacity-100');
      }, 50);
    });

    closeOverlayBtn.addEventListener('click', () => {
      celebrationOverlay.classList.remove('opacity-100');
      celebrationOverlay.classList.add('opacity-0');
      setTimeout(() => {
        celebrationOverlay.classList.add('hidden');
      }, 1000);
    });
  </script>
</body>
</html>
