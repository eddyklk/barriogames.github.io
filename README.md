<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BarrioGames - Estudio de Desarrollo</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Bangers&family=Poppins:wght@400;600;800&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #080c14;
            color: #f8fafc;
            overflow-x: hidden;
        }

        .brand-font {
            font-family: 'Bangers', cursive;
            letter-spacing: 2px;
        }

        .glass-card {
            background: rgba(30, 41, 59, 0.4);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: all 0.3s ease;
        }

        .glass-card:hover {
            transform: translateY(-5px);
            border-color: rgba(0, 243, 255, 0.4);
            box-shadow: 0 10px 30px -10px rgba(0, 243, 255, 0.2);
        }

        .neon-text {
            text-shadow: 0 0 15px rgba(0, 243, 255, 0.5);
        }
    </style>
</head>
<body class="min-h-screen flex flex-col">

    <header class="pt-20 pb-16 px-4 text-center relative overflow-hidden">
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-96 h-96 bg-cyan-500/20 rounded-full blur-[100px] -z-10"></div>
        <div class="absolute top-0 right-0 w-64 h-64 bg-pink-500/10 rounded-full blur-[80px] -z-10"></div>

        <h1 class="text-7xl md:text-9xl brand-font text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-600 mb-4 neon-text animate__animated animate__fadeInDown">
            BARRIOGAMES
        </h1>
        <p class="text-slate-400 text-lg md:text-xl max-w-2xl mx-auto font-medium mb-8 animate__animated animate__fadeInUp animate__delay-1s">
            Desarrollo de software, aplicaciones móviles y juegos con identidad propia.
        </p>
    </header>

    <main class="flex-grow max-w-6xl mx-auto px-4 w-full pb-20">
        
        <h2 class="text-2xl font-black uppercase tracking-widest text-white mb-6 flex items-center">
            <span class="text-pink-500 mr-3">🎮</span> Nuestros Juegos
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 mb-16">
            
            <a href="/shot-hot" class="glass-card rounded-3xl p-6 block group">
                <div class="h-40 bg-gradient-to-br from-pink-900 to-slate-900 rounded-2xl mb-4 flex items-center justify-center border border-pink-500/30 group-hover:border-pink-500 transition-colors">
                    <span class="text-6xl">🥃</span>
                </div>
                <h3 class="text-2xl font-black brand-font tracking-wide text-white mb-2">SHOT HOT</h3>
                <p class="text-slate-400 text-sm">El juego de beber definitivo. Reglas intocables, retos extremos y máximo caos para tus fiestas.</p>
            </a>

            <div class="glass-card rounded-3xl p-6 border-dashed border-2 border-slate-700 opacity-50 flex flex-col items-center justify-center min-h-[300px]">
                <span class="text-4xl mb-3">🛠️</span>
                <p class="text-slate-500 font-bold uppercase tracking-widest text-sm">Próximamente</p>
            </div>

        </div>

        <h2 class="text-2xl font-black uppercase tracking-widest text-white mb-6 flex items-center">
            <span class="text-blue-500 mr-3">📱</span> Aplicaciones
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
            
            <a href="#" class="glass-card rounded-3xl p-6 block">
                <div class="h-32 bg-slate-800 rounded-2xl mb-4 flex items-center justify-center">
                    <span class="text-4xl">💡</span>
                </div>
                <h3 class="text-xl font-bold text-white mb-1">LuzRD</h3>
                <p class="text-slate-400 text-sm">Tu app de consulta y gestión de energía.</p>
            </a>

            <a href="#" class="glass-card rounded-3xl p-6 block">
                <div class="h-32 bg-slate-800 rounded-2xl mb-4 flex items-center justify-center">
                    <span class="text-4xl">📊</span>
                </div>
                <h3 class="text-xl font-bold text-white mb-1">MiContadorRD</h3>
                <p class="text-slate-400 text-sm">Gestión financiera y contable simplificada.</p>
            </a>

            <a href="#" class="glass-card rounded-3xl p-6 block">
                <div class="h-32 bg-slate-800 rounded-2xl mb-4 flex items-center justify-center">
                    <span class="text-4xl">📝</span>
                </div>
                <h3 class="text-xl font-bold text-white mb-1">Frases365</h3>
                <p class="text-slate-400 text-sm">Inspiración diaria al alcance de tu mano.</p>
            </a>

        </div>
    </main>

    <footer class="border-t border-white/5 py-8 text-center text-slate-500 text-sm mt-auto">
        <p>© 2026 BarrioGames Studio. Creado con 💻 y ☕.</p>
    </footer>

</body>
</html>
