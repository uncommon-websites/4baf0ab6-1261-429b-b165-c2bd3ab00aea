<script>
  const features = [
    "AI-powered sequence generation", "CAD to instruction automation", "3D interactive visualization", "Real-time assembly tracking", "Operator feedback loops", "Version control for instructions",
    "Automated step generation", "Multi-CAD support", "NX integration", "SolidWorks integration", "Creo integration", "Assembly dependency analysis",
    "Interactive 3D models", "Step-by-step guidance", "Visual work instructions", "Operator dashboards", "Production analytics", "Time tracking per step",
    "Quality control checkpoints", "Error reduction metrics", "Assembly validation", "DFM analysis integration", "Engineering change sync", "Revision management",
    "SOC 2 Type 2 compliance", "AWS GovCloud support", "ITAR compliance", "Self-hosting options", "Secure deployment", "Role-based access control",
    "Shop floor tablets", "Mobile device support", "Browser-based access", "Offline mode", "Real-time collaboration", "Multi-language support",
    "Runs dashboard", "Production metrics", "Bottleneck identification", "Completion tracking", "Performance analytics", "Custom reporting",
    "Tribal knowledge capture", "Annotation tools", "Comment threads", "Approval workflows", "Change history", "Audit trails",
    "Automated documentation", "PDF export", "Print-friendly formats", "Digital twin integration", "PLM connectivity", "ERP integration",
    "Training mode", "Onboarding tools", "Skill tracking", "Operator certification", "Knowledge base", "Best practices library",
    "Aerospace assemblies", "Defense manufacturing", "Automotive production", "Medical devices", "Agriculture equipment", "Shipbuilding operations"
  ];
</script>

<section class="pt-24 pb-12 bg-white text-center overflow-hidden">
  <div class="max-w-[1400px] mx-auto px-6">
    <h2 class="text-5xl font-bold mb-16 tracking-tight text-gray-900 leading-tight">
      ...And Much,<br>Much More.
    </h2>

    <div class="flex flex-wrap justify-center gap-x-4 gap-y-3 text-xs text-gray-400 max-w-6xl mx-auto mb-32 opacity-70">
       {#each features as feature}
         <span class="hover:text-gray-900 transition-colors cursor-default">{feature}</span>
         <span class="text-gray-300">•</span>
       {/each}
    </div>

    <!-- CTA Section -->
    <div class="max-w-2xl mx-auto mb-24">
       <!-- Device Image Placeholder -->
       <div class="w-64 h-64 mx-auto mb-8 bg-gray-100 rounded-3xl shadow-2xl flex items-center justify-center relative border-4 border-gray-200">
          <div class="absolute inset-2 bg-gray-800 rounded-2xl flex flex-col items-center justify-center overflow-hidden">
             <!-- Screen -->
             <div class="w-full h-1/2 bg-black flex items-center justify-center border-b border-gray-700">
                <span class="text-4xl">🏭</span>
             </div>
             <!-- Keys -->
             <div class="w-full h-1/2 grid grid-cols-3 gap-1 p-2 bg-gray-700">
                <div class="bg-[oklch(0.696_0.17_162.48)] rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
             </div>
          </div>
       </div>
       
       <p class="text-lg text-gray-600 mb-8 leading-relaxed">
          Ready to transform your assembly operations? Join 60+ manufacturers using BuildOS to strengthen American manufacturing.
       </p>
       <button class="bg-black text-white px-6 py-3 rounded-lg hover:bg-gray-800 transition-colors font-semibold text-sm">
          Request Demo
       </button>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-[#0B0F19] text-white py-12 border-t border-gray-800">
     <div class="max-w-[1200px] mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6">
        <div class="flex items-center gap-2">
           <div class="w-5 h-5 bg-white text-black rounded flex items-center justify-center">
              <svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M3 3L21 3L21 21L3 21L3 3Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M3 9L21 9M3 15L21 15M9 3L9 21M15 3L15 21" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
           </div>
           <span class="font-bold text-sm">Dirac © 2025</span>
           <span class="text-gray-500 text-xs ml-2">Built in Manhattan, New York</span>
        </div>
        
        <div class="flex items-center gap-6 text-xs text-gray-400">
           <a href="#" class="hover:text-white">Sign in</a>
           <a href="#" class="hover:text-white">Request Demo</a>
           <a href="#" class="hover:text-white">Careers</a>
           <a href="#" class="hover:text-white">Privacy</a>
           <a href="#" class="hover:text-white">LinkedIn</a>
        </div>
     </div>
  </footer>
</section>
