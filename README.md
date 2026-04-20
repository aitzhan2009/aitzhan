# aitzhan
minecraft reitiing kz
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Батырлар Рейтингі</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background-color: #050b18; /* Қанық көк-қара фон */
            color: white;
            font-family: 'Segoe UI', sans-serif;
        }
        .ornament-bg {
            /* Фонға өте күңгірт ою қосу */
            background-image: url('https://www.transparenttextures.com/patterns/black-linen.png');
        }
        .card-kazakh {
            background: linear-gradient(90deg, #0f172a 0%, #1e293b 100%);
            border-left: 4px solid #d4af37; /* Алтын жиек */
            transition: 0.3s;
        }
        .card-kazakh:hover {
            transform: translateX(10px);
            background: #1e293b;
        }
        .rank-number {
            font-style: italic;
            background: linear-gradient(180deg, #d4af37, #fef08a);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .badge-na { background-color: #7f1d1d; color: #fecaca; }
        .badge-eu { background-color: #14532d; color: #bbf7d0; }
    </style>
</head>
<body class="ornament-bg p-4 md:p-10">

    <div class="max-w-5xl mx-auto">
        <h1 class="text-3xl font-bold mb-8 flex items-center gap-4">
            <span class="text-yellow-500">◈</span> БАТЫРЛАР ТІЗІМІ <span class="text-yellow-500">◈</span>
        </h1>

        <div class="card-kazakh flex flex-wrap items-center p-4 mb-3 rounded-r-lg shadow-lg">
            <div class="text-4xl font-black rank-number w-12">1.</div>
            <img src="https://mc-heads.net/avatar/Marlowww" class="w-12 h-12 rounded-md mx-4 border border-gray-600">
            
            <div class="flex-grow min-w-[200px]">
                <div class="text-xl font-bold tracking-wide">Marlowww</div>
                <div class="text-sm text-gray-400">Ұлы Батыр <span class="text-blue-400 font-mono">(450 ұпай)</span></div>
            </div>

            <div class="badge-na px-3 py-1 rounded text-xs font-bold mr-6">KZ</div>

            <div class="flex gap-3 mt-2 md:mt-0">
                <div class="text-center">
                    <div class="text-xl">⚔️</div>
                    <div class="text-[10px] text-yellow-500 font-bold">ХАН 1</div>
                </div>
                <div class="text-center">
                    <div class="text-xl">🛡️</div>
                    <div class="text-[10px] text-yellow-500 font-bold">БАТЫР 1</div>
                </div>
                <div class="text-center">
                    <div class="text-xl">🏹</div>
                    <div class="text-[10px] text-gray-400 font-bold">LT 1</div>
                </div>
            </div>
        </div>

        <div class="card-kazakh flex flex-wrap items-center p-4 mb-3 rounded-r-lg shadow-lg border-l-gray-400">
            <div class="text-4xl font-black text-gray-400 w-12">2.</div>
            <img src="https://mc-heads.net/avatar/ItzRealMe" class="w-12 h-12 rounded-md mx-4 border border-gray-600">
            
            <div class="flex-grow min-w-[200px]">
                <div class="text-xl font-bold tracking-wide">ItzRealMe</div>
                <div class="text-sm text-gray-400">Сарбаз <span class="text-blue-400 font-mono">(330 ұпай)</span></div>
            </div>

            <div class="badge-eu px-3 py-1 rounded text-xs font-bold mr-6">KZ</div>

            <div class="flex gap-3 mt-2 md:mt-0">
                <div class="text-center">
                    <div class="text-xl">⚔️</div>
                    <div class="text-[10px] text-orange-400 font-bold">HT 3</div>
                </div>
                <div class="text-center">
                    <div class="text-xl">🛡️</div>
                    <div class="text-[10px] text-yellow-500 font-bold">HT 1</div>
                </div>
            </div>
        </div>
        
    </div>

</body>
</html>
