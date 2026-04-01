<!DOCTYPE html>
<html lang="ar" dir="rtl" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coin Carrière | العقارات الاستراتيجية للشركات بالمغرب</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@0.400.0/dist/umd/lucide.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Tajawal', sans-serif; }
        .text-gold { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
        .border-gold { border-color: #D4AF37; }
        .hover-gold:hover { background-color: #C59B27; }
    </style>
</head>
<body class="bg-white text-slate-900">

    <nav class="fixed top-0 w-full bg-[#0F172A]/95 backdrop-blur-md z-50 border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-white font-bold text-xl flex items-center gap-2">
                <i data-lucide="briefcase" class="text-gold w-6 h-6"></i>
                Coin Carrière <span class="text-gold">.</span>
            </div>
            <a href="#formulaire" class="bg-gold text-[#0F172A] font-bold px-5 py-2 rounded text-sm hover-gold transition-all">
                فرص حصرية
            </a>
        </div>
    </nav>

    <section class="relative min-h-screen flex items-center bg-cover bg-center pt-16" style="background-image: url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070');">
        <div class="absolute inset-0 bg-gradient-to-l from-[#0F172A]/95 via-[#0F172A]/80 to-transparent"></div>
        
        <div class="relative max-w-7xl mx-auto px-6 lg:px-8 w-full py-20 text-right">
            <div class="max-w-3xl">
                <span class="text-gold uppercase tracking-widest text-sm font-semibold mb-4 block">عقارات الشركات الاستراتيجية بالمغرب</span>
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold text-white mb-6 leading-tight">
                    حوّل نمو شركتك إلى <span class="text-gold">فرصة عقارية استراتيجية.</span>
                </h1>
                <p class="text-lg text-slate-300 mb-8 max-w-2xl">
                    ترافق "Coin Carrière" الشركات الطموحة في البحث عن أصولها العقارية المهنية، الاستحواذ عليها، وتحسين أدائها المالي.
                </p>
                
                <div class="flex flex-col sm:flex-row gap-4 mb-12">
                    <a href="#formulaire" class="bg-gold text-[#0F172A] font-bold px-8 py-4 rounded shadow-lg hover-gold transition-all text-center flex items-center justify-center gap-2">
                        <span>احصل على فرص حصرية</span>
                        <i data-lucide="arrow-left" class="w-5 h-5"></i>
                    </a>
                    <a href="#formulaire" class="border border-white text-white font-bold px-8 py-4 rounded hover:bg-white/10 transition-all text-center">
                        حجز استشارة مجانية
                    </a>
                </div>

                <div class="flex flex-wrap gap-6 text-white text-sm">
                    <div class="flex items-center gap-2"><i data-lucide="shield" class="text-gold"></i> +10 سنوات خبرة</div>
                    <div class="flex items-center gap-2"><i data-lucide="building" class="text-gold"></i> +200 شركة مرافقة</div>
                    <div class="flex items-center gap-2"><i data-lucide="globe" class="text-gold"></i> شبكة 100% بريميوم</div>
                </div>
            </div>
        </div>
    </section>

    <section id="formulaire" class="py-20 bg-[#0F172A] text-white">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">اطلب ملفك العقاري المخصص</h2>
            <p class="text-slate-400 mb-10">اترك بيانات شركتك وسيتصل بك مستشارنا الخبير خلال 24 ساعة كحد أقصى.</p>
            
            <form class="space-y-6 text-right">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-sm font-medium mb-2 text-slate-300">الاسم الكامل *</label>
                        <input type="text" class="w-full bg-[#1E293B] border border-slate-700 rounded py-3 px-4 text-white focus:outline-none focus:border-gold" required>
                    </div>
                    <div>
                        <label class="block text-sm font-medium mb-2 text-slate-300">اسم الشركة *</label>
                        <input type="text" class="w-full bg-[#1E293B] border border-slate-700 rounded py-3 px-4 text-white focus:outline-none focus:border-gold" required>
                    </div>
                </div>
                <div>
                    <label class="block text-sm font-medium mb-2 text-slate-300">الهاتف (واتساب مفضل) *</label>
                    <input type="tel" class="w-full bg-[#1E293B] border border-slate-700 rounded py-3 px-4 text-white text-left focus:outline-none focus:border-gold" dir="ltr" placeholder="+212 ..." required>
                </div>
                <button type="submit" class="w-full bg-gold text-[#0F172A] font-bold px-8 py-4 rounded hover-gold transition-all flex items-center justify-center gap-2">
                    <span>تفعيل وصولي المميز</span>
                    <i data-lucide="arrow-left" class="w-5 h-5"></i>
                </button>
            </form>
        </div>
    </section>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>
