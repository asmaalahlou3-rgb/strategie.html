<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Immo Pour Vous | Agence Immobilière Maroc</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@0.400.0/dist/umd/lucide.min.js"></script>
    <style>
        /* Couleurs personnalisées pour coller au thème luxe */
        .bg-emerald-dark { background-color: #041E18; }
        .text-gold { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
        .border-gold { border-color: #D4AF37; }
        .hover-gold:hover { background-color: #C5A059; }
    </style>
</head>
<body class="bg-[#0b1311] text-gray-100 font-sans">

    <header class="relative bg-emerald-dark overflow-hidden border-b border-gray-800">
        <div class="absolute inset-0 bg-black opacity-50"></div>
        
        <div class="relative max-w-7xl mx-auto px-4 py-20 sm:py-28 sm:px-6 lg:px-8 flex flex-col items-center text-center">
            <span class="text-gold uppercase tracking-widest text-sm font-semibold mb-3">Opportunités Exclusives au Maroc</span>
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold text-white mb-6">
                Concrétisez votre projet immobilier avec des experts de confiance
            </h1>
            <p class="text-lg md:text-xl text-gray-300 max-w-3xl mb-10">
                Accédez aux meilleurs biens à Casablanca, Marrakech et Tanger avant leur sortie sur le marché. Un accompagnement juridique et d'investissement sécurisé de A à Z.
            </p>
            <div class="flex flex-col sm:flex-row gap-4">
                <a href="#formulaire" class="bg-gold text-black font-bold px-8 py-4 rounded-md shadow-lg hover-gold transition-all duration-300">
                    Parler à un conseiller sous 24h
                </a>
                <a href="#catalogue" class="border border-white text-white font-bold px-8 py-4 rounded-md hover:bg-white hover:text-black transition-all duration-300">
                    Découvrir nos biens exclusifs
                </a>
            </div>
        </div>
    </header>

    <section class="py-16 bg-[#091512]">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                
                <div class="p-6 bg-emerald-dark rounded-xl border border-gray-800 hover:border-gold transition-colors duration-300">
                    <div class="w-12 h-12 bg-gold/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i data-lucide="shield-check" class="text-gold w-6 h-6"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2 text-white">Sécurité Totale</h3>
                    <p class="text-gray-400 text-sm">Vérification stricte des titres fonciers et accompagnement notarial complet pour un achat serein.</p>
                </div>

                <div class="p-6 bg-emerald-dark rounded-xl border border-gray-800 hover:border-gold transition-colors duration-300">
                    <div class="w-12 h-12 bg-gold/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i data-lucide="eye" class="text-gold w-6 h-6"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2 text-white">Transparence Absolue</h3>
                    <p class="text-gray-400 text-sm">Honoraires clairs, aucun frais caché et communication fluide tout au long de la transaction.</p>
                </div>

                <div class="p-6 bg-emerald-dark rounded-xl border border-gray-800 hover:border-gold transition-colors duration-300">
                    <div class="w-12 h-12 bg-gold/10 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i data-lucide="gem" class="text-gold w-6 h-6"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2 text-white">Biens Exclusifs</h3>
                    <p class="text-gray-400 text-sm">Portefeuille off-market unique de propriétés de prestige soigneusement sélectionnées.</p>
                </div>

            </div>
        </div>
    </section>

    <section id="catalogue" class="py-20 bg-[#0b1311]">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Nos Biens Exclusifs</h2>
                <p class="text-gray-400 max-w-2xl mx-auto">Découvrez une sélection de nos plus belles propriétés disponibles actuellement.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-emerald-dark rounded-xl overflow-hidden border border-gray-800 group">
                    <div class="h-64 bg-gray-700 relative">
                        <div class="absolute inset-0 flex items-center justify-center text-gray-500">Photo Villa Marrakech</div>
                        <span class="absolute top-4 left-4 bg-gold text-black text-xs font-bold px-3 py-1 rounded-full">Exclusivité</span>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Villa de Luxe - Palmeraie</h3>
                        <p class="text-gray-400 text-sm mb-4">Marrakech | 5 Ch | 600 m²</p>
                        <div class="flex justify-between items-center">
                            <span class="text-gold font-bold text-lg">Prix sur demande</span>
                            <a href="#formulaire" class="text-white hover:text-gold text-sm font-medium transition-colors">En savoir plus →</a>
                        </div>
                    </div>
                </div>

                <div class="bg-emerald-dark rounded-xl overflow-hidden border border-gray-800">
                    <div class="h-64 bg-gray-700 relative">
                        <div class="absolute inset-0 flex items-center justify-center text-gray-500">Photo Penthouse Casa</div>
                        <span class="absolute top-4 left-4 bg-gold text-black text-xs font-bold px-3 py-1 rounded-full">Neuf</span>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Penthouse Vue Mer</h3>
                        <p class="text-gray-400 text-sm mb-4">Casablanca | 3 Ch | 240 m²</p>
                        <div class="flex justify-between items-center">
                            <span class="text-gold font-bold text-lg">7 500 000 DH</span>
                            <a href="#formulaire" class="text-white hover:text-gold text-sm font-medium transition-colors">En savoir plus →</a>
                        </div>
                    </div>
                </div>

                <div class="bg-emerald-dark rounded-xl overflow-hidden border border-gray-800">
                    <div class="h-64 bg-gray-700 relative">
                        <div class="absolute inset-0 flex items-center justify-center text-gray-500">Photo Appartement Tanger</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Appartement Moderne</h3>
                        <p class="text-gray-400 text-sm mb-4">Tanger (Centre) | 2 Ch | 110 m²</p>
                        <div class="flex justify-between items-center">
                            <span class="text-gold font-bold text-lg">2 100 000 DH</span>
                            <a href="#formulaire" class="text-white hover:text-gold text-sm font-medium transition-colors">En savoir plus →</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="formulaire" class="py-20 bg-emerald-dark border-y border-gray-800">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-10">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Votre projet mérite l'excellence</h2>
                <p class="text-gray-300">Remplissez le formulaire ci-dessous. Un consultant senior vous contactera sous 24h pour une étude personnalisée.</p>
            </div>

            <form class="space-y-6">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-sm font-medium text-gray-300 mb-2">Nom & Prénom *</label>
                        <input type="text" class="w-full bg-[#0b1311] border border-gray-700 rounded-md py-3 px-4 text-white focus:outline-none focus:border-gold transition-colors" placeholder="Votre nom complet" required>
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-300 mb-2">Téléphone (WhatsApp souhaité) *</label>
                        <input type="tel" class="w-full bg-[#0b1311] border border-gray-700 rounded-md py-3 px-4 text-white focus:outline-none focus:border-gold transition-colors" placeholder="+212 6..." required>
                    </div>
                </div>

                <div>
                    <label class="block text-sm font-medium text-gray-300 mb-2">Adresse Email *</label>
                    <input type="email" class="w-full bg-[#0b1311] border border-gray-700 rounded-md py-3 px-4 text-white focus:outline-none focus:border-gold transition-colors" placeholder="nom@exemple.com" required>
                </div>

                <div>
                    <label class="block text-sm font-medium text-gray-300 mb-2">Votre projet *</label>
                    <select class="w-full bg-[#0b1311] border border-gray-700 rounded-md py-3 px-4 text-white focus:outline-none focus:border-gold transition-colors" required>
                        <option value="">Sélectionnez un type de projet</option>
                        <option value="achat">Achat d'un bien</option>
                        <option value="vente">Vente d'un bien</option>
                        <option value="investissement">Investissement locatif</option>
                    </select>
                </div>

                <button type="submit" class="w-full bg-gold text-black font-bold px-8 py-4 rounded-md shadow-lg hover-gold transition-all duration-300">
                    Être recontacté sous 24h
                </button>
                <p class="text-xs text-gray-500 text-center">Vos données restent strictement confidentielles et ne seront jamais partagées avec des tiers.</p>
            </form>
        </div>
    </section>

    <footer class="py-8 bg-[#0b1311] text-center text-gray-500 text-sm">
        <p>&copy; 2026 Immo Pour Vous. Tous droits réservés.</p>
    </footer>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>
