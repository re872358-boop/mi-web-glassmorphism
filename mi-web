

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
    <title>LOBA Enterprise | Neural System</title>
    <script src="https://unpkg.com/@tailwindcss/browser@4"></script>
    <link rel="stylesheet" href="styles/style.css">
    <style>
        @keyframes slideUp {
            from { transform: translateY(40px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        .animate-slide-up { animation: slideUp 0.6s cubic-bezier(0.16, 1, 0.3, 1) forwards; }
        
        .glass-premium {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
        }
        .input-glass {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
    </style>
</head>
<body class="bg-[#020617] text-slate-300 antialiased overflow-x-hidden">

    <header id="main-header" class="fixed top-0 w-full z-[120] glass-premium px-6 py-4 flex justify-between items-center border-b border-white/5 transition-all duration-500">
        <div class="flex items-center gap-4">
            <button onclick="toggleMenu()" class="flex flex-col gap-1.5 focus:outline-none">
                <div class="w-5 h-0.5 bg-white"></div>
                <div class="w-3 h-0.5 bg-blue-500"></div>
                <div class="w-5 h-0.5 bg-white"></div>
            </button>
            <div class="text-[10px] font-black tracking-[0.2em] text-white uppercase italic">
                NICOLÁS <span class="text-blue-500 italic text-[11px] ml-1">♊</span>
            </div>
        </div>
        <div class="flex items-center gap-4">
            <div class="h-6 w-6 rounded-full border border-white/10 flex items-center justify-center text-[10px] font-bold text-slate-500 cursor-help" title="Auditoría v4 Activa">?</div>
            <div class="h-2 w-2 rounded-full bg-emerald-500 animate-pulse shadow-[0_0_8px_#10b981]"></div>
        </div>
    </header>

    <nav id="side-menu" class="fixed inset-y-0 left-0 w-64 bg-[#020617]/98 backdrop-blur-3xl z-[130] -translate-x-full transition-transform duration-300 border-r border-white/10 shadow-2xl">
        <div class="p-8 space-y-6 pt-24">
            <div class="text-[9px] text-blue-500 font-mono tracking-widest uppercase mb-8 italic border-b border-blue-500/20 pb-2">Admin_Terminal_v4</div>
            <a href="#" class="block text-xs font-black tracking-widest text-white uppercase italic hover:text-blue-400 transition-colors">Módulos Activos</a>
            <a href="#" class="block text-xs font-bold tracking-widest text-slate-400 uppercase hover:text-white transition-colors">Consultoría</a>
            <div class="pt-10 border-t border-white/5">
                <button onclick="accesoAdmin()" class="text-[10px] text-slate-600 font-mono italic">Acceso Búnker _</button>
            </div>
        </div>
    </nav>

    <main class="pt-[85px]">
        <section class="relative h-[35vh] w-full overflow-hidden bg-slate-900">
            <img src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?auto=format&fit=crop&q=80&w=1000" 
                 class="w-full h-full object-cover opacity-40 scale-110" alt="Neural Core">
            <div class="absolute inset-0 bg-gradient-to-t from-[#020617] via-transparent to-black/60"></div>
            <div class="absolute bottom-8 left-6 animate-fade-in pr-6">
                <p class="text-blue-400 font-mono text-[9px] uppercase tracking-widest mb-2 italic">Análisis de Red Completo</p>
                <h1 class="text-3xl font-black text-white italic tracking-tighter leading-none">
                    ¡HOLA! <br> <span class="text-blue-500 uppercase italic">¿Qué vamos a auditar hoy?</span>
                </h1>
            </div>
        </section>

        <section class="px-4 py-8">
            <h2 class="text-slate-500 font-mono text-[9px] tracking-[0.5em] uppercase text-center mb-6 italic">Visual Showcase_Core</h2>
            
            <div class="grid grid-cols-2 gap-3 mb-8">
                <div class="glass-premium rounded-2xl overflow-hidden aspect-[4/5] border border-white/5">
                    <img src="https://images.unsplash.com/photo-1542751371-adc38448a05e?auto=format&fit=crop&q=80&w=500" class="w-full h-full object-cover opacity-80">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
                    <div class="absolute bottom-3 left-3">
                        <p class="text-[8px] font-black text-white italic uppercase">Gaming Engine</p>
                    </div>
                </div>
                <div class="glass-premium rounded-2xl overflow-hidden aspect-[4/5] border border-white/5">
                    <img src="https://images.unsplash.com/photo-1551288049-bbbda5366392?auto=format&fit=crop&q=80&w=500" class="w-full h-full object-cover opacity-80">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
                    <div class="absolute bottom-3 left-3">
                        <p class="text-[8px] font-black text-white italic uppercase">Gestión Pro</p>
                    </div>
                </div>
            </div>

            <div class="space-y-4 mb-8">
                <div class="glass-premium p-5 rounded-3xl border-l-4 border-l-blue-500">
                    <h4 class="text-white font-black italic text-sm uppercase mb-1">Gaming Engine</h4>
                    <p class="text-[11px] text-slate-400">Optimización C++ para entornos móviles de alta carga.</p>
                </div>
                <div class="glass-premium p-5 rounded-3xl border-l-4 border-l-emerald-500">
                    <h4 class="text-white font-black italic text-sm uppercase mb-1">GESTIÓN PRO</h4>
                    <p class="text-[11px] text-slate-400">Administración financiera privada y auditoría técnica.</p>
                </div>
            </div>

            <div class="px-2">
                <button onclick="toggleChat()" class="w-full py-5 bg-blue-600/20 border border-blue-500/40 rounded-2xl text-[10px] font-black text-white uppercase tracking-[0.2em] italic backdrop-blur-md shadow-[0_0_30px_rgba(59,130,246,0.2)] active:scale-95 transition-all">
                    Solicitar Auditoría _
                </button>
            </div>
        </section>

        <div id="chat-container" class="fixed inset-0 z-[150] hidden flex items-end justify-center p-4">
            <div class="absolute inset-0 bg-black/70 backdrop-blur-sm" onclick="toggleChat()"></div>
            <div class="glass-premium w-full max-w-[400px] rounded-[3rem] overflow-hidden border border-blue-500/30 shadow-2xl animate-slide-up relative z-[10]">
                <div class="p-8 space-y-6">
                    <div class="flex justify-between items-start border-b border-white/5 pb-4">
                        <div class="text-[11px] font-mono text-blue-300 uppercase italic">
                            <span class="text-blue-500 font-black tracking-widest">IA >></span> Fichero Entrada
                        </div>
                        <button onclick="toggleChat()" class="text-slate-500 text-[9px] font-black uppercase">Cerrar _</button>
                    </div>
                    
                    <div class="space-y-3">
                        <input type="text" id="lead-nombre" placeholder="NOMBRE COMPLETO" class="input-glass w-full text-[11px] font-bold p-4 rounded-2xl text-white outline-none focus:border-blue-500 transition-all uppercase">
                        <input type="email" id="lead-correo" placeholder="CORREO" class="input-glass w-full text-[11px] font-bold p-4 rounded-2xl text-white outline-none focus:border-blue-500 transition-all uppercase">
                        <select id="lead-software" class="input-glass w-full text-[11px] bg-[#020617] font-bold text-slate-500 p-4 rounded-2xl outline-none">
                            <option value="" disabled selected>SELECCIONAR MÓDULO...</option>
                            <option value="Juegos">Gaming Engine</option>
                            <option value="Gestion">Sistema de Gestión</option>
                        </select>
                        <button onclick="registrarPedido()" class="w-full py-5 mt-4 font-black text-[11px] uppercase tracking-[0.2em] bg-blue-600 text-white rounded-2xl shadow-lg shadow-blue-500/20 active:scale-95 italic">
                            Confirmar en Búnker _
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <div id="overlay" onclick="toggleMenu()" class="fixed inset-0 bg-black/80 z-[115] hidden backdrop-blur-sm"></div>

    <script>
        function toggleMenu() {
            document.getElementById('side-menu').classList.toggle('-translate-x-full');
            document.getElementById('overlay').classList.toggle('hidden');
        }

        function toggleChat() {
            const chat = document.getElementById('chat-container');
            chat.classList.toggle('hidden');
        }

        window.addEventListener('scroll', () => {
            const header = document.getElementById('main-header');
            if (window.scrollY > 20) {
                header.classList.add('bg-[#020617]/80', 'backdrop-blur-xl', 'py-3');
            } else {
                header.classList.remove('bg-[#020617]/80', 'backdrop-blur-xl', 'py-3');
            }
        });
    </script>
    <script src="script.js/javscrip.js"></script>
</body>
</html>
 