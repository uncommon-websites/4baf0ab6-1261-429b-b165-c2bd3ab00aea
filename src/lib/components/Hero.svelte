<script>
</script>

<section class="pt-20 pb-16 text-center max-w-[1200px] mx-auto px-6">
  <h1 class="text-6xl font-bold tracking-tight text-gray-900 mb-6 leading-[1.1]">
    AI-Powered Assembly<br>Work Instructions
  </h1>
  <p class="text-lg text-gray-600 mb-8 max-w-2xl mx-auto leading-relaxed">
    BuildOS automates work instruction creation from CAD files, reducing weeks of manual work to hours with AI-powered sequence generation and 3D visualization.
  </p>
  <button class="bg-black text-white px-6 py-3 rounded-lg hover:bg-gray-800 transition-colors font-semibold text-sm mb-20 cursor-pointer">
    Request Demo
  </button>

  <!-- Exploded View Image Placeholder -->
  <div class="relative w-full aspect-[2/1] bg-gray-50 rounded-xl overflow-hidden flex items-center justify-center border border-gray-100">
    <!-- Abstract representation of exploded view -->
    <div class="relative w-[600px] h-[400px] perspective-[1000px]">
       <!-- Bottom Layer -->
       <div class="absolute top-[60%] left-[50%] transform -translate-x-1/2 -translate-y-1/2 w-64 h-64 bg-gray-200 rounded-2xl rotate-x-[60deg] rotate-z-[45deg] shadow-xl border border-gray-300"></div>
       
       <!-- Middle Layer (PCB) -->
       <div class="absolute top-[50%] left-[50%] transform -translate-x-1/2 -translate-y-1/2 w-56 h-56 bg-green-800/80 rounded-xl rotate-x-[60deg] rotate-z-[45deg] shadow-lg border border-green-700 backdrop-blur-sm flex items-center justify-center">
          <div class="w-full h-full grid grid-cols-4 gap-2 p-4 opacity-50">
             <div class="bg-yellow-400/50 rounded-sm col-span-2"></div>
             <div class="bg-gray-300/50 rounded-full"></div>
             <div class="bg-black/30 rounded-sm"></div>
          </div>
       </div>
       
       <!-- Top Layer (Casing) -->
       <div class="absolute top-[40%] left-[50%] transform -translate-x-1/2 -translate-y-1/2 w-64 h-64 bg-white/90 rounded-2xl rotate-x-[60deg] rotate-z-[45deg] shadow-2xl border border-gray-200 backdrop-blur-sm"></div>
       
       <!-- Floating Elements -->
       <div class="absolute top-[30%] left-[60%] w-8 h-8 bg-gray-400 rounded-full shadow-lg animate-bounce duration-[3000ms]"></div>
       <div class="absolute top-[35%] left-[40%] w-4 h-12 bg-gray-300 rounded-full shadow-lg rotate-45"></div>
       <div class="absolute top-[25%] left-[55%] w-2 h-20 bg-gray-300 rounded-full shadow-lg rotate-12"></div>
    </div>
    
    <div class="absolute inset-0 bg-gradient-to-t from-white via-transparent to-transparent pointer-events-none"></div>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mt-20 text-left">
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">01</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">CAD to Instructions</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Turn CAD files directly into interactive, animated assembly sequences. AI automatically generates optimal build order and step-by-step instructions.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">02</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">3D Visualization</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Interactive 3D models show exactly how parts fit together. Operators can rotate, zoom, and explore assemblies from any angle in real-time.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">03</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">95% Faster</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        What used to take 3-4 days now takes 1-2 hours. Automate 80% of work instruction creation and keep instructions synchronized with engineering changes.
      </p>
    </div>
  </div>
</section>
