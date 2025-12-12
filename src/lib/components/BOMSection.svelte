<script>
</script>

<section class="bg-[#0B0F19] text-white py-24">
  <div class="max-w-[1200px] mx-auto px-6">
    <div class="text-center mb-16">
      <h2 class="text-5xl font-bold mb-6 tracking-tight">
        Intelligent Assembly Sequences
      </h2>
      <p class="text-gray-400 text-lg max-w-2xl mx-auto leading-relaxed">
        AI analyzes your CAD assembly to automatically generate optimal build sequences. Every step is visualized in 3D with clear instructions for operators on the shop floor.
      </p>
    </div>

    <!-- BOM UI Mockup -->
    <div class="bg-white rounded-lg overflow-hidden shadow-2xl mb-20 text-gray-900 mx-auto max-w-[1000px]">
      <!-- Window Header -->
      <div class="bg-gray-50 border-b border-gray-200 px-4 py-2 flex items-center justify-between">
         <div class="flex items-center gap-2">
            <span class="text-xs font-semibold text-gray-700">Atlas Main BOM</span>
         </div>
         <div class="flex items-center gap-3">
            <div class="flex items-center gap-1 text-xs text-gray-500 bg-white border border-gray-200 px-2 py-1 rounded">
               <span>👁️</span> View
            </div>
            <div class="flex items-center gap-1 text-xs text-gray-500 bg-white border border-gray-200 px-2 py-1 rounded">
               <span>📊</span> All columns
            </div>
            <div class="flex items-center gap-1 text-xs text-gray-500 bg-white border border-gray-200 px-2 py-1 rounded">
               <span>⬇️</span> Export CSV
            </div>
            <button class="text-gray-400 hover:text-gray-600">✕</button>
         </div>
      </div>

      <!-- Table Header -->
      <div class="grid grid-cols-12 bg-gray-50 border-b border-gray-200 text-[10px] font-bold text-gray-500 uppercase tracking-wider py-2 px-4">
         <div class="col-span-1">Make/Buy</div>
         <div class="col-span-1">Alt</div>
         <div class="col-span-1">Lvl</div>
         <div class="col-span-2">Part #</div>
         <div class="col-span-3">Part Name</div>
         <div class="col-span-1">Rev</div>
         <div class="col-span-1">Qty</div>
         <div class="col-span-1">UOM</div>
         <div class="col-span-1">Part Family</div>
      </div>

      <!-- Table Body - Empty State / Search for effect -->
      <div class="h-[400px] bg-white relative">
         <!-- Search Overlay Effect -->
         <div class="absolute top-4 left-4 right-4 bg-white border border-gray-200 shadow-sm rounded p-2 flex items-center gap-2 max-w-md z-10">
            <span class="text-gray-400">🔍</span>
            <span class="text-sm text-gray-900">Atl|</span>
            <div class="w-[1px] h-4 bg-blue-500 animate-pulse"></div>
         </div>
         
         <!-- Blurred/Faded rows to simulate content behind search -->
         <div class="opacity-30 pointer-events-none">
             {#each Array(8) as _, i}
             <div class="grid grid-cols-12 border-b border-gray-100 py-3 px-4 text-xs text-gray-600">
                <div class="col-span-1 flex items-center"><div class="w-2 h-2 rounded-full bg-green-500 mr-2"></div> Make</div>
                <div class="col-span-1">-</div>
                <div class="col-span-1">{i + 1}</div>
                <div class="col-span-2 font-mono">310-221{i}</div>
                <div class="col-span-3">Component Name {i + 1}</div>
                <div class="col-span-1">A</div>
                <div class="col-span-1">{Math.floor(Math.random() * 10) + 1}</div>
                <div class="col-span-1">EA</div>
                <div class="col-span-1">Mech</div>
             </div>
             {/each}
         </div>
      </div>
    </div>

    <!-- Features Grid -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-x-12 gap-y-16 text-left">
       <!-- Feature 1 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2L2 7L12 12L22 7L12 2Z"/><path d="M2 17L12 22L22 17"/><path d="M2 12L12 17L22 12"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Automated Sequencing</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             AI analyzes part dependencies and constraints to generate optimal assembly order automatically, eliminating manual planning.
          </p>
       </div>

       <!-- Feature 2 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><path d="M8 21h8"/><path d="M12 17v4"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Interactive 3D Steps</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Every assembly step includes interactive 3D visualization. Operators can rotate, zoom, and explore from any angle.
          </p>
       </div>

       <!-- Feature 3 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21.5 2v6h-6"/><path d="M2.5 22v-6h6"/><path d="M2 11.5a10 10 0 0 1 18.8-4.3L21.5 8"/><path d="M22 12.5a10 10 0 0 1-18.8 4.2L2.5 16"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Live Sync with CAD</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             When engineering makes changes, work instructions update automatically. No more lagging behind design revisions.
          </p>
       </div>

       <!-- Feature 4 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Detailed Annotations</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Add notes, callouts, and warnings to specific steps. Capture tribal knowledge from experienced operators.
          </p>
       </div>

       <!-- Feature 5 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Time Tracking</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Track actual assembly times per step to optimize sequences and improve production planning accuracy.
          </p>
       </div>

       <!-- Feature 6 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Operator Feedback</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Shop floor workers can report issues and suggest improvements directly within the instruction interface.
          </p>
       </div>
    </div>
  </div>
</section>
