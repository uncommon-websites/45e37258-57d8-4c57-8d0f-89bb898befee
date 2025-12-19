<script>
  import { onMount } from 'svelte';

  // SVGs
  const arrowUpIcon = `<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5 text-white"><path d="m5 12 7-7 7 7"/><path d="M12 19V5"/></svg>`;
  const playIcon = `<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-4 h-4"><polygon points="5 3 19 12 5 21 5 3"/></svg>`;
</script>

<div class="w-full bg-white">
  <!-- Hero Section -->
  <section class="pt-32 pb-20 px-6 md:pt-40 md:pb-32">
    <div class="max-w-[1200px] mx-auto">
      <div class="text-center max-w-4xl mx-auto mb-16">
        <h1 class="text-5xl md:text-[64px] leading-[1.1] font-medium tracking-tight text-gray-900 mb-6">
          AI agents that automate<br />workflows. <span class="block">Built for Indonesia.</span>
        </h1>
        <p class="text-xl md:text-[22px] leading-relaxed text-gray-600 max-w-2xl mx-auto">
          Sarana AI identifies high-impact workflows, then deploys<br class="hidden md:block" />specialized agents that work within your legacy systems.
        </p>
      </div>

      <!-- Hero Card -->
      <div class="bg-gray-50 rounded-[40px] p-8 md:p-20 w-full aspect-[16/10] md:aspect-[16/9] relative overflow-hidden shadow-sm">
        <img src="/generated/image-indonesian-operations-manager-reviewing--1766111547213-0.webp" alt="Indonesian operations manager" class="absolute inset-0 w-full h-full object-cover" />
        <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-black/20 to-transparent"></div>
        
        <!-- Stats Overlay -->
        <div class="absolute bottom-12 left-8 right-8 md:left-16 md:right-16 flex flex-wrap gap-8 text-white">
          <div>
            <div class="text-3xl md:text-4xl font-bold mb-1">30 Days</div>
            <div class="text-sm opacity-90">To Proven ROI</div>
          </div>
          <div>
            <div class="text-3xl md:text-4xl font-bold mb-1">15-40%</div>
            <div class="text-sm opacity-90">Cost Reduction</div>
          </div>
          <div>
            <div class="text-3xl md:text-4xl font-bold mb-1">12</div>
            <div class="text-sm opacity-90">Industries Served</div>
          </div>
        </div>

        <!-- CTA Button -->
        <a href="https://wa.me/6285230598559" class="absolute top-8 right-8 md:top-12 md:right-16 flex items-center gap-2 bg-primary-600 hover:bg-primary-700 text-white px-5 py-2.5 rounded-full text-sm font-medium transition-all hover:shadow-lg">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
          Start Pilot
        </a>
      </div>
    </div>
  </section>

  <!-- Industries Section -->
  <section class="py-16 border-b border-gray-100">
    <div class="max-w-[1200px] mx-auto px-6">
      <div class="flex flex-col md:flex-row gap-16 items-start">
        <!-- Left: Header with Sector List -->
        <div class="w-full md:w-2/5">
          <h2 class="text-3xl md:text-4xl font-medium text-gray-900 mb-4">Trusted across Indonesia's critical industries</h2>
          <p class="text-gray-600 mb-8">Serving enterprises in 12 sectors that power Indonesia's economy</p>
          
          <ul class="space-y-3 text-gray-700">
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Financial Services</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Healthcare</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Manufacturing</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Retail & Hospitality</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Food & Beverage</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Education</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Energy</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Technology</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Fashion</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Agriculture</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Logistics</span>
            </li>
            <li class="flex items-center gap-3">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600 flex-shrink-0"><polyline points="20 6 9 17 4 12"/></svg>
              <span>Metals & Plastics</span>
            </li>
          </ul>
        </div>
        
        <!-- Right: Client Logos Grid -->
        <div class="w-full md:w-3/5">
          <div class="grid grid-cols-3 gap-8">
            <!-- Logo 1 -->
            <div class="bg-white rounded-xl border border-gray-200 p-6 flex items-center justify-center aspect-square hover:shadow-md transition-shadow">
              <div class="w-full h-full flex items-center justify-center">
                <span class="text-gray-400 text-sm font-medium">Client Logo</span>
              </div>
            </div>
            
            <!-- Logo 2 -->
            <div class="bg-white rounded-xl border border-gray-200 p-6 flex items-center justify-center aspect-square hover:shadow-md transition-shadow">
              <div class="w-full h-full flex items-center justify-center">
                <span class="text-gray-400 text-sm font-medium">Client Logo</span>
              </div>
            </div>
            
            <!-- Logo 3 -->
            <div class="bg-white rounded-xl border border-gray-200 p-6 flex items-center justify-center aspect-square hover:shadow-md transition-shadow">
              <div class="w-full h-full flex items-center justify-center">
                <span class="text-gray-400 text-sm font-medium">Client Logo</span>
              </div>
            </div>
            
            <!-- Logo 4 -->
            <div class="bg-white rounded-xl border border-gray-200 p-6 flex items-center justify-center aspect-square hover:shadow-md transition-shadow">
              <div class="w-full h-full flex items-center justify-center">
                <span class="text-gray-400 text-sm font-medium">Client Logo</span>
              </div>
            </div>
            
            <!-- Logo 5 -->
            <div class="bg-white rounded-xl border border-gray-200 p-6 flex items-center justify-center aspect-square hover:shadow-md transition-shadow">
              <div class="w-full h-full flex items-center justify-center">
                <span class="text-gray-400 text-sm font-medium">Client Logo</span>
              </div>
            </div>
            
            <!-- Logo 6 -->
            <div class="bg-white rounded-xl border border-gray-200 p-6 flex items-center justify-center aspect-square hover:shadow-md transition-shadow">
              <div class="w-full h-full flex items-center justify-center">
                <span class="text-gray-400 text-sm font-medium">Client Logo</span>
              </div>
            </div>
            
            <!-- Logo 7 -->
            <div class="bg-white rounded-xl border border-gray-200 p-6 flex items-center justify-center aspect-square hover:shadow-md transition-shadow">
              <div class="w-full h-full flex items-center justify-center">
                <span class="text-gray-400 text-sm font-medium">Client Logo</span>
              </div>
            </div>
            
            <!-- Logo 8 -->
            <div class="bg-white rounded-xl border border-gray-200 p-6 flex items-center justify-center aspect-square hover:shadow-md transition-shadow">
              <div class="w-full h-full flex items-center justify-center">
                <span class="text-gray-400 text-sm font-medium">Client Logo</span>
              </div>
            </div>
            
            <!-- Logo 9 -->
            <div class="bg-white rounded-xl border border-gray-200 p-6 flex items-center justify-center aspect-square hover:shadow-md transition-shadow">
              <div class="w-full h-full flex items-center justify-center">
                <span class="text-gray-400 text-sm font-medium">Client Logo</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Feature Section 1 -->
  <section class="py-24 px-6">
    <div class="max-w-[1200px] mx-auto">
      <div class="flex flex-col md:flex-row gap-16 items-start">
        <!-- Visual -->
        <div class="w-full md:w-1/2 bg-gray-50 rounded-[32px] aspect-square relative overflow-hidden group">
          <img src="/generated/image-professional-indonesian-business-team-co-1766111549969-1.webp" alt="Workflow mapping" class="absolute inset-0 w-full h-full object-cover" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/40 to-transparent"></div>
        </div>

        <!-- Content -->
        <div class="w-full md:w-1/2 pt-8">
          <div class="flex justify-between items-start mb-6">
            <h2 class="text-4xl md:text-[40px] leading-tight font-medium text-gray-900 max-w-md">
              Identify high-impact workflows
            </h2>
            <span class="bg-primary-600 text-white px-3 py-1.5 rounded-full text-xs font-medium">Discovery</span>
          </div>
          
          <p class="text-gray-600 text-lg mb-12 leading-relaxed">
            We map your operations to find where AI agents can deliver the biggest P&L impact—targeting $100K+ annualized savings per engagement.
          </p>

          <div class="space-y-10">
            <!-- Feature 1 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-900"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-2">30-day proof of concept</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  Every project starts with measurable results. We build a pilot agent with clear KPIs before full commitment.
                </p>
              </div>
            </div>

            <!-- Feature 2 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-900"><path d="M12 2v20M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-2">Focus on ROI, not hype</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  We target 15-40% cost reduction and 2-5x revenue per employee uplift in targeted workflows. No generic AI promises.
                </p>
              </div>
            </div>

            <!-- Feature 3 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-900"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-2">Co-ownership model</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  We co-own one agent with you, working alongside your team through discovery, build, and optimization.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial Section -->
  <section class="py-12 px-6">
    <div class="max-w-[1200px] mx-auto">
      <div class="bg-gray-50 rounded-[32px] overflow-hidden relative">
        <div class="grid md:grid-cols-2 gap-0">
          <div class="p-12 md:p-16">
            <div class="mb-8 font-bold text-lg text-primary-600">Indonesian Banking Leader</div>
            <blockquote class="text-2xl md:text-3xl font-medium leading-tight text-gray-900 mb-12">
              "Sarana AI reduced our compliance review time by 40% and accelerated loan processing by 3x—all while working within our legacy systems."
            </blockquote>
            <div class="flex items-center gap-4">
              <img src="/generated/image-confident-indonesian-female-executive-in-1766111554788-3.webp" alt="Operations Director" class="w-12 h-12 rounded-full object-cover" />
              <div>
                <div class="font-medium text-gray-900">Operations Director</div>
                <div class="text-sm text-gray-500">Leading Indonesian Bank</div>
              </div>
            </div>
          </div>
          <div class="relative min-h-[300px] md:min-h-0">
            <img src="/generated/image-confident-indonesian-female-executive-in-1766111554788-3.webp" alt="Banking executive" class="absolute inset-0 w-full h-full object-cover" />
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Feature Section 2 (Specialized Agents) -->
  <section class="py-24 px-6 bg-gray-50">
    <div class="max-w-[1200px] mx-auto">
      <div class="flex flex-col md:flex-row gap-16 items-start">
        <!-- Visual -->
        <div class="w-full md:w-1/2 bg-white rounded-[32px] aspect-square relative overflow-hidden shadow-sm">
          <img src="/generated/image-indonesian-hr-professional-working-effic-1766111552500-2.webp" alt="AI agents at work" class="absolute inset-0 w-full h-full object-cover" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/40 to-transparent"></div>
          <div class="absolute bottom-6 left-6 right-6 text-white">
            <div class="text-sm opacity-90 mb-2">Agent Status</div>
            <div class="flex items-center gap-2">
              <div class="w-2 h-2 bg-green-400 rounded-full animate-pulse"></div>
              <span class="text-sm font-medium">Active & Learning</span>
            </div>
          </div>
        </div>

        <!-- Content -->
        <div class="w-full md:w-1/2 pt-8">
          <div class="flex justify-between items-start mb-6">
            <h2 class="text-4xl md:text-[40px] leading-tight font-medium text-gray-900 max-w-md">
              Deploy specialized agents
            </h2>
            <span class="bg-primary-600 text-white px-3 py-1.5 rounded-full text-xs font-medium">Automation</span>
          </div>
          
          <p class="text-gray-600 text-lg mb-12 leading-relaxed">
            Each agent owns a piece of work—removing busywork so your people can focus on judgment calls and high-value tasks.
          </p>

          <div class="space-y-10">
            <!-- Feature 1 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-900"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-2">Built for Indonesian compliance</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  Our agents understand OJK, BI, and BPOM requirements—handling regulatory complexity while you focus on growth.
                </p>
              </div>
            </div>

            <!-- Feature 2 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-900"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-2">Works with legacy systems</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  No complete overhauls required. Our agents integrate with your existing enterprise infrastructure and processes.
                </p>
              </div>
            </div>

            <!-- Feature 3 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-900"><path d="M16 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="8.5" cy="7" r="4"/><polyline points="17 11 19 13 23 9"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-2">Augments your workforce</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  Agents multiply human judgment instead of replacing it—making your team more visible, effective, and valued.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Feature Section 3 (FDS-PAC Partnership) -->
  <section class="py-24 px-6 bg-gray-900 text-white">
    <div class="max-w-[1200px] mx-auto">
      <div class="flex flex-col md:flex-row gap-16 items-start">
        <!-- Visual -->
        <div class="w-full md:w-1/2 bg-gray-800 rounded-[32px] aspect-square relative overflow-hidden border border-white/10">
           <!-- Network Visualization -->
           <div class="absolute inset-0 flex items-center justify-center p-8">
             <div class="relative w-full h-full">
               <!-- Central Node -->
               <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-20 h-20 bg-primary-600 rounded-full flex items-center justify-center text-white font-bold text-sm">
                 FDS-PAC
               </div>
               <!-- Surrounding Nodes -->
               <div class="absolute top-[20%] left-[30%] w-12 h-12 bg-gray-700 rounded-full flex items-center justify-center text-xs border border-primary-600/30">FSI</div>
               <div class="absolute top-[25%] right-[25%] w-12 h-12 bg-gray-700 rounded-full flex items-center justify-center text-xs border border-primary-600/30">Health</div>
               <div class="absolute bottom-[25%] left-[20%] w-12 h-12 bg-gray-700 rounded-full flex items-center justify-center text-xs border border-primary-600/30">Retail</div>
               <div class="absolute bottom-[20%] right-[30%] w-12 h-12 bg-gray-700 rounded-full flex items-center justify-center text-xs border border-primary-600/30">Energy</div>
               <!-- Connection Lines (visual effect) -->
               <svg class="absolute inset-0 w-full h-full opacity-20" xmlns="http://www.w3.org/2000/svg">
                 <line x1="50%" y1="50%" x2="30%" y2="20%" stroke="currentColor" stroke-width="1" class="text-primary-600"/>
                 <line x1="50%" y1="50%" x2="75%" y2="25%" stroke="currentColor" stroke-width="1" class="text-primary-600"/>
                 <line x1="50%" y1="50%" x2="20%" y2="75%" stroke="currentColor" stroke-width="1" class="text-primary-600"/>
                 <line x1="50%" y1="50%" x2="70%" y2="80%" stroke="currentColor" stroke-width="1" class="text-primary-600"/>
               </svg>
             </div>
           </div>
        </div>

        <!-- Content -->
        <div class="w-full md:w-1/2 pt-8">
          <div class="flex justify-between items-start mb-6">
            <h2 class="text-4xl md:text-[40px] leading-tight font-medium text-white max-w-md">
              Trusted across Indonesia
            </h2>
            <span class="bg-primary-600 text-white px-3 py-1.5 rounded-full text-xs font-medium">Partnership</span>
          </div>
          
          <p class="text-gray-300 text-lg mb-12 leading-relaxed">
            As part of FDS-PAC Group, we have access to enterprise relationships across 12 critical industries—positioning us as trusted across public and private sectors.
          </p>

          <div class="space-y-4">
            <!-- Feature 1 (Active) -->
            <div class="bg-gray-800/50 p-6 rounded-xl border border-white/10">
              <h3 class="font-medium text-white mb-2 text-sm">Indonesia-native understanding</h3>
              <p class="text-gray-400 text-xs leading-relaxed">
                Deep knowledge of local regulatory environment, business practices, and operational challenges unique to Indonesian enterprises.
              </p>
            </div>

            <!-- Feature 2 -->
            <div class="p-6 rounded-xl border border-white/10 hover:bg-gray-800/30 transition-colors cursor-pointer">
              <h3 class="font-medium text-gray-300 mb-2 text-sm">Enterprise relationships</h3>
              <p class="text-gray-400 text-xs leading-relaxed">
                Established trust with leading organizations across banking, healthcare, manufacturing, and other key sectors.
              </p>
            </div>

            <!-- Feature 3 -->
            <div class="p-6 rounded-xl border border-white/10 hover:bg-gray-800/30 transition-colors cursor-pointer">
              <h3 class="font-medium text-gray-300 mb-2 text-sm">Compliance-first approach</h3>
              <p class="text-gray-400 text-xs leading-relaxed">
                Built-in understanding of OJK, BI, and BPOM requirements ensures regulatory adherence from day one.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Security Section -->
  <section class="py-24 px-6 bg-white">
    <div class="max-w-[1200px] mx-auto">
      <div class="flex flex-col md:flex-row gap-16 items-start">
        <!-- Visual (Left) -->
        <div class="w-full md:w-1/2 bg-gray-50 rounded-[32px] aspect-square relative flex items-center justify-center p-8 border border-gray-200">
           <div class="text-center max-w-sm">
             <div class="mb-6">
               <svg xmlns="http://www.w3.org/2000/svg" width="64" height="64" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" class="mx-auto text-primary-600"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/><path d="M12 8v4"/><path d="M12 16h.01"/></svg>
             </div>
             <div class="text-gray-900 text-lg font-medium mb-2">Enterprise-Grade Security</div>
             <div class="text-gray-600 text-sm">Built for Indonesian regulatory compliance from day one</div>
           </div>
        </div>

        <!-- Content (Right) -->
        <div class="w-full md:w-1/2 pt-8">
          <h2 class="text-4xl md:text-[40px] leading-tight font-medium text-gray-900 mb-6">
            Secure & compliant
          </h2>
          
          <p class="text-gray-600 text-lg mb-12 leading-relaxed">
            Sarana AI is designed with enterprise-grade security and compliance built in. Our agents work within your guardrails and meet Indonesian regulatory standards.
          </p>

          <div class="space-y-6">
            <div class="flex gap-4 items-start">
              <div class="w-10 h-10 rounded-full bg-primary-50 flex items-center justify-center flex-shrink-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-1">Data encryption & secure storage</h3>
                <p class="text-gray-600 text-sm">All data encrypted in transit and at rest with configurable retention policies.</p>
              </div>
            </div>

            <div class="flex gap-4 items-start">
              <div class="w-10 h-10 rounded-full bg-primary-50 flex items-center justify-center flex-shrink-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/><polyline points="10 9 9 9 8 9"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-1">Audit logs for all decisions</h3>
                <p class="text-gray-600 text-sm">Complete transparency with detailed logs of every agent action and decision.</p>
              </div>
            </div>

            <div class="flex gap-4 items-start">
              <div class="w-10 h-10 rounded-full bg-primary-50 flex items-center justify-center flex-shrink-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M22 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-1">GDPR & Indonesia privacy compliance</h3>
                <p class="text-gray-600 text-sm">Built to meet both international and local data privacy requirements.</p>
              </div>
            </div>

            <div class="flex gap-4 items-start">
              <div class="w-10 h-10 rounded-full bg-primary-50 flex items-center justify-center flex-shrink-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-primary-600"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-1">OJK, BI & BPOM compliance</h3>
                <p class="text-gray-600 text-sm">Regulatory compliance built for Indonesian financial services, banking, and healthcare.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Results Section -->
  <section class="py-24 px-6 bg-gray-50">
    <div class="max-w-[1200px] mx-auto">
      <div class="flex justify-between items-end mb-16">
        <div class="max-w-xl">
          <h2 class="text-4xl md:text-[40px] leading-tight font-medium text-gray-900 mb-6">
            Proven results across industries
          </h2>
          <p class="text-gray-600 text-lg leading-relaxed">
            Indonesian enterprises trust Sarana AI to deliver measurable ROI through workflow automation and AI agents.
          </p>
        </div>
        <span class="bg-primary-600 text-white px-3 py-1.5 rounded-full text-xs font-medium mb-2">Case Studies</span>
      </div>

      <div class="grid md:grid-cols-3 gap-8">
        <!-- Card 1: Banking -->
        <div class="group cursor-pointer">
          <div class="relative aspect-square rounded-2xl overflow-hidden mb-6 bg-gray-100">
            <img src="/generated/image-indonesian-banking-professional-reviewin-1766111557040-4.webp" alt="Banking case study" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
            <div class="absolute top-6 left-6">
              <span class="bg-primary-600 text-white px-3 py-1.5 rounded-full text-xs font-medium">Financial Services</span>
            </div>
            <div class="absolute bottom-6 left-6 text-white right-6">
              <div class="grid grid-cols-2 gap-4 mb-4">
                <div>
                  <div class="text-xs font-medium opacity-80 mb-1">Compliance Time</div>
                  <div class="text-2xl font-bold flex items-center gap-1"><span class="text-sm">↓</span> 40%</div>
                </div>
                <div>
                  <div class="text-xs font-medium opacity-80 mb-1">Loan Processing</div>
                  <div class="text-2xl font-bold flex items-center gap-1"><span class="text-sm">↑</span> 3x</div>
                </div>
              </div>
            </div>
          </div>
          <h3 class="text-xl text-gray-900 leading-snug group-hover:text-primary-600 transition-colors">
            How a leading Indonesian bank accelerated compliance and lending.
          </h3>
        </div>

        <!-- Card 2: Enterprise Operations -->
        <div class="group cursor-pointer">
          <div class="relative aspect-square rounded-2xl overflow-hidden mb-6 bg-gray-100">
            <img src="/generated/image-indonesian-enterprise-team-celebrating-s-1766111559303-5.webp" alt="Enterprise case study" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
            <div class="absolute top-6 left-6">
              <span class="bg-primary-600 text-white px-3 py-1.5 rounded-full text-xs font-medium">Manufacturing</span>
            </div>
            <div class="absolute bottom-6 left-6 text-white right-6">
              <div class="grid grid-cols-2 gap-4 mb-4">
                <div>
                  <div class="text-xs font-medium opacity-80 mb-1">Cost Reduction</div>
                  <div class="text-2xl font-bold flex items-center gap-1"><span class="text-sm">↓</span> 35%</div>
                </div>
                <div>
                  <div class="text-xs font-medium opacity-80 mb-1">ROI Timeline</div>
                  <div class="text-2xl font-bold">30 Days</div>
                </div>
              </div>
            </div>
          </div>
          <h3 class="text-xl text-gray-900 leading-snug group-hover:text-primary-600 transition-colors">
            How an enterprise manufacturer automated procurement workflows.
          </h3>
        </div>

        <!-- Card 3: Healthcare -->
        <div class="group cursor-pointer">
          <div class="relative aspect-square rounded-2xl overflow-hidden mb-6 bg-gray-100">
            <img src="/generated/image-indonesian-operations-leader-analyzing-w-1766111561784-6.webp" alt="Healthcare case study" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
            <div class="absolute top-6 left-6">
              <span class="bg-primary-600 text-white px-3 py-1.5 rounded-full text-xs font-medium">Healthcare</span>
            </div>
            <div class="absolute bottom-6 left-6 text-white right-6">
              <div class="grid grid-cols-2 gap-4 mb-4">
                <div>
                  <div class="text-xs font-medium opacity-80 mb-1">Query Handling</div>
                  <div class="text-2xl font-bold flex items-center gap-1"><span class="text-sm">↑</span> 60%</div>
                </div>
                <div>
                  <div class="text-xs font-medium opacity-80 mb-1">Response Time</div>
                  <div class="text-2xl font-bold flex items-center gap-1"><span class="text-sm">↓</span> 50%</div>
                </div>
              </div>
            </div>
          </div>
          <h3 class="text-xl text-gray-900 leading-snug group-hover:text-primary-600 transition-colors">
            How a healthcare provider streamlined patient service operations.
          </h3>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA Section -->
  <section class="py-32 px-6 text-center">
    <div class="max-w-[1200px] mx-auto">
      <h2 class="text-4xl md:text-5xl font-medium text-gray-900 mb-6 tracking-tight">
        Start your 30-day pilot today
      </h2>
      <p class="text-gray-600 text-lg max-w-2xl mx-auto mb-10">
        Discover where AI agents can deliver the biggest impact in your operations. We'll map your workflows and prove ROI in 30 days—no commitment required.
      </p>
      <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
        <a href="https://wa.me/6285230598559" class="inline-flex items-center gap-2 bg-primary-600 hover:bg-primary-700 text-white px-8 py-3 rounded-full font-medium transition-colors">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
          Start WhatsApp Pilot
        </a>
        <a href="#" class="inline-block bg-white hover:bg-gray-50 text-gray-900 px-8 py-3 rounded-full font-medium transition-colors border border-gray-200">
          Download Overview
        </a>
      </div>
      <p class="text-sm text-gray-500 mt-6">
        Join enterprises across 12 industries already automating with Sarana AI
      </p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-[#F9F9F9] pt-20 pb-10 px-6 border-t border-gray-100">
    <div class="max-w-[1200px] mx-auto">
      <div class="grid grid-cols-2 md:grid-cols-6 gap-12 mb-20">
        <div class="col-span-2">
          <a href="/" class="flex items-center gap-3 text-primary-600 mb-6">
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-7 h-7">
              <path fill-rule="evenodd" clip-rule="evenodd" d="M6.99251 12.196C6.85314 12.5757 6.62925 12.9208 6.33682 13.2067H6.33835C6.00191 13.5351 5.58566 13.7756 5.12816 13.9059C4.67065 14.0362 4.18671 14.0522 3.72118 13.9523C3.25564 13.8524 2.82357 13.64 2.46501 13.3345C2.10645 13.0291 1.83299 12.6406 1.66998 12.2051C1.50697 11.7696 1.45969 11.3012 1.5325 10.8432C1.60532 10.3852 1.79587 9.95244 2.08653 9.58516C2.37718 9.21781 2.75852 8.9277 3.1952 8.74177C3.63188 8.55585 4.10979 8.48002 4.58462 8.52142L4.57074 8.50792C5.0567 8.54782 5.54575 8.48407 6.00378 8.32124C6.4618 8.15846 6.87776 7.90043 7.2226 7.56521C7.56746 7.22998 7.83285 6.82564 8.00036 6.38041C8.16786 5.93517 8.23344 5.45976 8.1924 4.98737L8.20628 5.00087C8.15181 4.43594 8.27796 3.86844 8.56753 3.37575C8.85701 2.88307 9.29579 2.48919 9.82407 2.24782C10.3523 2.00645 10.9443 1.92933 11.5192 2.02701C12.0942 2.12467 12.6243 2.39237 13.037 2.79358C13.4497 3.19479 13.7251 3.70999 13.8256 4.26892C13.926 4.82785 13.8467 5.4033 13.5984 5.9168C13.3501 6.4303 12.9449 6.85685 12.4381 7.13828C11.9313 7.41971 11.3474 7.54233 10.7663 7.4894L10.781 7.5029C10.2949 7.46279 9.80563 7.52632 9.34741 7.68904C8.88919 7.85176 8.47309 8.10975 8.12805 8.44499C7.78301 8.78025 7.51742 9.18466 7.34983 9.63001C7.18224 10.0754 7.11669 10.551 7.15774 11.0235L7.14309 11.01C7.1833 11.4112 7.13189 11.8162 6.99251 12.196ZM11.5077 14.7121L11.493 14.6986C11.9061 14.739 12.3232 14.6897 12.7143 14.5543C13.1053 14.4188 13.4605 14.2007 13.7542 13.9154C14.0477 13.6302 14.2726 13.285 14.4121 12.905C14.5518 12.525 14.6028 12.1196 14.5615 11.718L14.5762 11.7315C14.5351 11.2591 14.6007 10.7838 14.7681 10.3385C14.9356 9.89327 15.2011 9.48893 15.5459 9.15368C15.8908 8.8185 16.3068 8.56042 16.7648 8.39767C17.2228 8.23481 17.7118 8.17111 18.1978 8.21099L18.1832 8.19749C18.7645 8.25059 19.3485 8.12801 19.8556 7.84656C20.3627 7.56511 20.7681 7.13845 21.0165 6.62479C21.265 6.11114 21.3444 5.53548 21.2439 4.97634C21.1435 4.4172 20.868 3.9018 20.4551 3.50044C20.0422 3.09909 19.512 2.8313 18.9368 2.73364C18.3616 2.63596 17.7695 2.71315 17.241 2.95467C16.7126 3.19618 16.2737 3.59027 15.9842 4.08319C15.6946 4.57609 15.5685 5.14383 15.6232 5.70895L15.6093 5.6947C15.6504 6.16712 15.585 6.64259 15.4175 7.08788C15.2501 7.53318 14.9846 7.93758 14.6398 8.27287C14.2949 8.60805 13.8789 8.86612 13.4208 9.02888C12.9627 9.19163 12.4736 9.25523 11.9876 9.21526L12.0015 9.22951C11.5885 9.18908 11.1713 9.23836 10.7803 9.37381C10.3893 9.50919 10.034 9.72744 9.74039 10.0127C9.44674 10.2979 9.22199 10.6431 9.08234 11.0231C8.94276 11.4031 8.89176 11.8085 8.93304 12.2101L8.91915 12.1966C8.96005 12.6689 8.89439 13.1443 8.72688 13.5895C8.5593 14.0346 8.29389 14.4389 7.94908 14.7741C7.60425 15.1093 7.18835 15.3673 6.73039 15.5302C6.27242 15.693 5.78342 15.7569 5.29749 15.7171L5.31138 15.7306C4.73003 15.6775 4.14599 15.8001 3.63892 16.0815C3.13186 16.363 2.72644 16.7896 2.478 17.3033C2.22954 17.817 2.15013 18.3926 2.25061 18.9518C2.35109 19.5109 2.62657 20.0263 3.03945 20.4276C3.45234 20.829 3.98253 21.0968 4.55773 21.1944C5.13293 21.2921 5.72512 21.2149 6.25353 20.9734C6.78193 20.7319 7.22085 20.3379 7.51038 19.8449C7.79994 19.352 7.92601 18.7843 7.87139 18.2191L7.88605 18.2326C7.845 17.7602 7.91058 17.2849 8.07809 16.8396C8.24551 16.3944 8.511 15.99 8.85581 15.6548C9.20069 15.3196 9.61664 15.0615 10.0746 14.8988C10.5327 14.7359 11.0217 14.6722 11.5077 14.7121ZM17.1996 10.7633C16.9071 11.0493 16.6832 11.3944 16.5437 11.7741C16.4042 12.1538 16.3526 12.5587 16.3925 12.9601L16.3786 12.9466C16.4197 13.419 16.3541 13.8944 16.1866 14.3396C16.0191 14.7849 15.7537 15.1892 15.4089 15.5244C15.064 15.8596 14.648 16.1177 14.19 16.2804C13.732 16.4433 13.2429 16.507 12.757 16.4671L12.7708 16.4806C12.1896 16.4281 11.6057 16.551 11.0989 16.8328C10.5921 17.1145 10.1871 17.5414 9.93902 18.0551C9.69097 18.5689 9.61188 19.1444 9.71265 19.7035C9.81349 20.2625 10.0892 20.7777 10.5022 21.1788C10.9152 21.5799 11.4454 21.8474 12.0205 21.9448C12.5957 22.0423 13.1877 21.9649 13.716 21.7234C14.2443 21.4817 14.683 21.0877 14.9724 20.5947C15.2618 20.1018 15.3878 19.5342 15.3332 18.9692L15.3478 18.9827C15.3068 18.5103 15.3723 18.0349 15.5398 17.5896C15.7073 17.1444 15.9728 16.7401 16.3176 16.4048C16.6625 16.0696 17.0784 15.8115 17.5364 15.6488C17.9945 15.486 18.4835 15.4222 18.9695 15.4621L18.9548 15.4486C19.4296 15.4901 19.9076 15.4144 20.3444 15.2286C20.7811 15.0427 21.1625 14.7527 21.4533 14.3854C21.744 14.0181 21.9347 13.5854 22.0075 13.1274C22.0805 12.6694 22.0332 12.2009 21.8703 11.7653C21.7073 11.3298 21.4339 10.9413 21.0754 10.6358C20.7168 10.3303 20.2848 10.1178 19.8192 10.0179C19.3536 9.91795 18.8697 9.93385 18.4121 10.0641C17.9546 10.1945 17.5383 10.4349 17.2019 10.7633H17.1996Z" fill="currentColor"/>
            </svg>
            <span class="text-xl tracking-tight font-semibold text-gray-900">Sarana AI</span>
          </a>
          <p class="text-sm text-gray-600 max-w-xs">
            AI agents for Indonesian enterprise workflow automation. Part of FDS-PAC Group.
          </p>
        </div>
        
        <div>
          <h4 class="font-medium text-gray-900 mb-4 text-sm">Solutions</h4>
          <ul class="space-y-3 text-sm text-gray-600">
            <li><a href="#" class="hover:text-gray-900">Workflow Mapping</a></li>
            <li><a href="#" class="hover:text-gray-900">AI Agents</a></li>
            <li><a href="#" class="hover:text-gray-900">Compliance Automation</a></li>
            <li><a href="#" class="hover:text-gray-900">Legacy Integration</a></li>
            <li><a href="#" class="hover:text-gray-900">30-Day Pilot</a></li>
          </ul>
        </div>

        <div>
          <h4 class="font-medium text-gray-900 mb-4 text-sm">Industries</h4>
          <ul class="space-y-3 text-sm text-gray-600">
            <li><a href="#" class="hover:text-gray-900">Financial Services</a></li>
            <li><a href="#" class="hover:text-gray-900">Healthcare</a></li>
            <li><a href="#" class="hover:text-gray-900">Manufacturing</a></li>
            <li><a href="#" class="hover:text-gray-900">Retail & F&B</a></li>
            <li><a href="#" class="hover:text-gray-900">Education</a></li>
            <li><a href="#" class="hover:text-gray-900">All Industries</a></li>
          </ul>
        </div>

        <div>
          <h4 class="font-medium text-gray-900 mb-4 text-sm">Resources</h4>
          <ul class="space-y-3 text-sm text-gray-600">
            <li><a href="#" class="hover:text-gray-900">Case Studies</a></li>
            <li><a href="#" class="hover:text-gray-900">Articles</a></li>
            <li><a href="#" class="hover:text-gray-900">Product One-Pagers</a></li>
            <li><a href="#" class="hover:text-gray-900">Workshops</a></li>
          </ul>
        </div>

        <div>
          <h4 class="font-medium text-gray-900 mb-4 text-sm">Company</h4>
          <ul class="space-y-3 text-sm text-gray-600">
            <li><a href="#" class="hover:text-gray-900">About Us</a></li>
            <li><a href="#" class="hover:text-gray-900">Leadership</a></li>
            <li><a href="#" class="hover:text-gray-900">FDS-PAC Group</a></li>
            <li><a href="#" class="hover:text-gray-900">Careers</a></li>
            <li><a href="https://wa.me/6285230598559" class="hover:text-gray-900">Contact</a></li>
          </ul>
        </div>
      </div>

      <div class="flex flex-col md:flex-row justify-between items-center pt-8 border-t border-gray-200">
        <div class="flex flex-col md:flex-row items-center gap-6 mb-4 md:mb-0">
          <button class="bg-white border border-gray-200 rounded-md px-3 py-1.5 text-sm text-gray-600 flex items-center gap-2 hover:border-gray-300">
            Indonesia (Bahasa)
            <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
          </button>
          <div class="text-xs text-gray-500">
            © 2025 Sarana AI
            <a href="#" class="ml-4 hover:text-gray-900">Privacy Policy</a>
            <a href="#" class="ml-4 hover:text-gray-900">Terms & Conditions</a>
            <a href="#" class="ml-4 hover:text-gray-900">Security</a>
          </div>
        </div>

        <div class="flex items-center gap-4 text-gray-400">
          <a href="#" class="hover:text-gray-900"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg></a>
          <a href="#" class="hover:text-gray-900"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg></a>
          <a href="#" class="hover:text-gray-900"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.33 29 29 0 0 0-.46-5.33zM9.75 15.02l5.75-3.27-5.75-3.27z"/></svg></a>
        </div>
      </div>
    </div>
  </footer>
</div>



