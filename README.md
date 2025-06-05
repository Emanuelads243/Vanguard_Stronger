# Vanguard_Stronger
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OversizedFit | Camisas Oversized para Treinos</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        
        .hero-image {
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1600861195091-690c92f1d2cc?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            height: 90vh;
        }
        
        .product-card:hover {
            transform: translateY(-10px);
            transition: all 0.3s ease;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }
        
        .floating {
            animation: float 3s ease-in-out infinite;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navbar -->
    <nav class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between items-center h-16">
                <!-- Logo -->
                <div class="flex items-center space-x-2">
                    <i class="fas fa-tshirt text-2xl text-indigo-600"></i>
                    <span class="text-xl font-bold text-gray-800">OversizedFit</span>
                </div>
                
                <!-- Mobile menu button -->
                <div class="md:hidden">
                    <button id="menu-btn" class="text-gray-500 hover:text-indigo-600 focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
                
                <!-- Desktop Menu -->
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-gray-800 hover:text-indigo-600 font-medium">Home</a>
                    <a href="#products" class="text-gray-800 hover:text-indigo-600 font-medium">Produtos</a>
                    <a href="#about" class="text-gray-800 hover:text-indigo-600 font-medium">Sobre</a>
                    <a href="#contact" class="text-gray-800 hover:text-indigo-600 font-medium">Contato</a>
                    <div class="flex items-center space-x-4">
                        <a href="#" class="text-gray-800 hover:text-indigo-600">
                            <i class="fas fa-shopping-cart"></i>
                        </a>
                        <a href="#" class="text-gray-800 hover:text-indigo-600">
                            <i class="fas fa-user"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-gray-200">
            <div class="px-4 py-2 space-y-2">
                <a href="#home" class="block text-gray-800 hover:text-indigo-600 font-medium py-2">Home</a>
                <a href="#products" class="block text-gray-800 hover:text-indigo-600 font-medium py-2">Produtos</a>
                <a href="#about" class="block text-gray-800 hover:text-indigo-600 font-medium py-2">Sobre</a>
                <a href="#contact" class="block text-gray-800 hover:text-indigo-600 font-medium py-2">Contato</a>
                <div class="flex space-x-4 py-2">
                    <a href="#" class="text-gray-800 hover:text-indigo-600">
                        <i class="fas fa-shopping-cart"></i>
                    </a>
                    <a href="#" class="text-gray-800 hover:text-indigo-600">
                        <i class="fas fa-user"></i>
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-image flex items-center justify-center text-white">
        <div class="text-center px-4">
            <h1 class="text-4xl md:text-6xl font-bold mb-4">Conforto e Estilo nos Seus Treinos</h1>
            <p class="text-xl md:text-2xl mb-8">Camisetas oversized premium para máxima liberdade de movimento</p>
            <a href="#products" class="bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-3 px-6 rounded-full transition duration-300 inline-flex items-center">
                Ver Coleção <i class="fas fa-chevron-right ml-2"></i>
            </a>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="text-center p-6 rounded-lg">
                    <div class="bg-indigo-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-heart text-indigo-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Conforto Premium</h3>
                    <p class="text-gray-600">Tecidos ultra macios que respeitam sua pele e garantem conforto durante todo o treino.</p>
                </div>
                <div class="text-center p-6 rounded-lg">
                    <div class="bg-indigo-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-tshirt text-indigo-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Corte Oversized</h3>
                    <p class="text-gray-600">Modelagem perfeita que oferece liberdade total de movimento sem perder o estilo.</p>
                </div>
                <div class="text-center p-6 rounded-lg">
                    <div class="bg-indigo-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-leaf text-indigo-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Tecido Respirável</h3>
                    <p class="text-gray-600">Tecnologia que mantém seu corpo fresco mesmo nos treinos mais intensos.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Nossa Coleção</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">Descubra nossas camisetas oversized projetadas para revolucionar seus treinos</p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="relative overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1527719339843-4da3a378deae?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=774&q=80" alt="Performance Fit" class="w-full h-80 object-cover transform hover:scale-105 transition duration-500">
                        <span class="absolute top-4 right-4 bg-indigo-600 text-white text-xs font-bold px-2 py-1 rounded-full">NOVO</span>
                    </div>
                    <div class="p-6">
                        <h3 class="text-lg font-bold text-gray-900 mb-2">Performance Fit</h3>
                        <div class="flex items-center mb-4">
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                            <span class="text-gray-500 text-sm ml-2">(42 avaliações)</span>
                        </div>
                        <p class="text-gray-600 mb-4">Camiseta oversized em tecido ultra respirável para treinos de alta intensidade.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xl font-bold text-gray-900">R$ 129,90</span>
                            <button class="bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-2 px-4 rounded-full transition duration-300">
                                Adicionar <i class="fas fa-shopping-cart ml-1"></i>
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="relative overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1527661591475-527312dd65f5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=772&q=80" alt="Urban Athlete" class="w-full h-80 object-cover transform hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-6">
                        <h3 class="text-lg font-bold text-gray-900 mb-2">Urban Athlete</h3>
                        <div class="flex items-center mb-4">
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="far fa-star"></i>
                            </div>
                            <span class="text-gray-500 text-sm ml-2">(36 avaliações)</span>
                        </div>
                        <p class="text-gray-600 mb-4">Estilo streetwear com conforto atlético para treinar e sair com estilo.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xl font-bold text-gray-900">R$ 149,90</span>
                            <button class="bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-2 px-4 rounded-full transition duration-300">
                                Adicionar <i class="fas fa-shopping-cart ml-1"></i>
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="relative overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1529374255404-311a2a4f1fd9?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1310&q=80" alt="Tank Pro" class="w-full h-80 object-cover transform hover:scale-105 transition duration-500">
                        <span class="absolute top-4 right-4 bg-red-500 text-white text-xs font-bold px-2 py-1 rounded-full">-20%</span>
                    </div>
                    <div class="p-6">
                        <h3 class="text-lg font-bold text-gray-900 mb-2">Tank Pro</h3>
                        <div class="flex items-center mb-4">
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                            <span class="text-gray-500 text-sm ml-2">(58 avaliações)</span>
                        </div>
                        <p class="text-gray-600 mb-4">Camiseta oversized com tecnologia anti-odor para treinos prolongados.</p>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-xl font-bold text-gray-900">R$ 99,90</span>
                                <span class="text-sm line-through text-gray-500 ml-2">R$ 124,90</span>
                            </div>
                            <button class="bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-2 px-4 rounded-full transition duration-300">
                                Adicionar <i class="fas fa-shopping-cart ml-1"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="inline-block border-2 border-indigo-600 text-indigo-600 hover:bg-indigo-600 hover:text-white font-bold py-3 px-8 rounded-full transition duration-300">
                    Ver Toda a Coleção
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:flex items-center justify-between">
                <div class="lg:w-1/2 mb-10 lg:mb-0">
                    <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80" alt="Sobre Nós" class="rounded-lg shadow-xl w-full h-auto">
                </div>
                <div class="lg:w-1/2 lg:pl-12">
                    <h2 class="text-3xl font-bold text-gray-900 mb-6">Nossa Missão</h2>
                    <p class="text-gray-600 mb-4">Na OversizedFit, acreditamos que o conforto não deve ser comprometido pelo estilo, especialmente quando se trata de roupas para treino. Nossas camisetas oversized são projetadas para atletas que valorizam liberdade de movimento sem abrir mão de um visual moderno.</p>
                    <p class="text-gray-600 mb-8">Trabalhamos com tecidos premium que combinam durabilidade, respirabilidade e maciez para proporcionar a melhor experiência em seus treinos, sejam eles na academia, ao ar livre ou em casa.</p>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <div class="flex items-center justify-center h-6 w-6 rounded-full bg-indigo-100 text-indigo-600">
                                    <i class="fas fa-check text-sm"></i>
                                </div>
                            </div>
                            <div class="ml-3">
                                <p class="text-gray-600">Tecidos de alta performance com tecnologia dry-fit</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <div class="flex items-center justify-center h-6 w-6 rounded-full bg-indigo-100 text-indigo-600">
                                    <i class="fas fa-check text-sm"></i>
                                </div>
                            </div>
                            <div class="ml-3">
                                <p class="text-gray-600">Corte oversized que não perde a forma após lavagens</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="flex-shrink-0 mt-1">
                                <div class="flex items-center justify-center h-6 w-6 rounded-full bg-indigo-100 text-indigo-600">
                                    <i class="fas fa-check text-sm"></i>
                                </div>
                            </div>
                            <div class="ml-3">
                                <p class="text-gray-600">Produção sustentável e ética</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-16 bg-indigo-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">O Que Dizem Nossos Clientes</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">A experiência de quem já treina com conforto e estilo</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"As camisetas da OversizedFit mudaram completamente meus treinos. O conforto é incomparável e o estilo é perfeito para quem gosta de look oversized sem parecer desleixado."</p>
                    <div class="flex items-center">
                        <img class="h-12 w-12 rounded-full object-cover" src="https://randomuser.me/api/portraits/women/43.jpg" alt="Depoimento">
                        <div class="ml-4">
                            <h4 class="font-bold text-gray-900">Ana Luiza</h4>
                            <p class="text-gray-500 text-sm">Personal Trainer</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"Comprei três e não parei mais. O tecido é respirável mesmo nos treinos mais pesados e o caimento fica perfeito. Já recomendei para todos do meu box de crossfit."</p>
                    <div class="flex items-center">
                        <img class="h-12 w-12 rounded-full object-cover" src="https://randomuser.me/api/portraits/men/32.jpg" alt="Depoimento">
                        <div class="ml-4">
                            <h4 class="font-bold text-gray-900">Marcos Vinícius</h4>
                            <p class="text-gray-500 text-sm">Crossfiter</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"Finalmente encontrei camisetas que combinam meu estilo streetwear com performance nos treinos. Não esquenta, não aperta e ainda mantém um visual incrível."</p>
                    <div class="flex items-center">
                        <img class="h-12 w-12 rounded-full object-cover" src="https://randomuser.me/api/portraits/men/76.jpg" alt="Depoimento">
                        <div class="ml-4">
                            <h4 class="font-bold text-gray-900">Rafael Souza</h4>
                            <p class="text-gray-500 text-sm">Estudante e Maratonista</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16 bg-indigo-600 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-bold mb-4">Pronto para Revolucionar Seus Treinos?</h2>
            <p class="text-xl mb-8 max-w-3xl mx-auto">Inscreva-se para receber promoções exclusivas e seja o primeiro a saber sobre novos lançamentos.</p>
            <form class="max-w-md mx-auto">
                <div class="flex flex-col sm:flex-row gap-4">
                    <input type="email" placeholder="Seu melhor e-mail" class="flex-grow px-4 py-3 rounded-full text-gray-800 focus:outline-none">
                    <button type="submit" class="bg-white text-indigo-600 hover:bg-gray-100 font-bold py-3 px-6 rounded-full transition duration-300">
                        Inscrever-se
                    </button>
                </div>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <i class="fas fa-tshirt text-2xl text-indigo-500"></i>
                        <span class="text-xl font-bold">OversizedFit</span>
                    </div>
                    <p class="text-gray-400">Roupas oversized premium para quem não abre mão de conforto e estilo nos treinos.</p>
                    <div class="flex space-x-4 mt-6">
                        <a href="#" class="text-gray-400 hover:text-indigo-500">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-indigo-500">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-indigo-500">
                            <i class="fab fa-tiktok"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-indigo-500">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">Produtos</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-indigo-500">Novidades</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-indigo-500">Mais Vendidos</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-indigo-500">Coleção Verão</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-indigo-500">Kits Promocionais</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">Ajuda</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-indigo-500">Trocas e Devoluções</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-indigo-500">Guia de Tamanhos</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-indigo-500">Entregas</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-indigo-500">Perguntas Frequentes</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">Contato</h3>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-center">
                            <i class="fas fa-map-marker-alt mr-2 text-indigo-500"></i>
                            Av. Paulista, 1000 - São Paulo/SP
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone-alt mr-2 text-indigo-500"></i>
                            (11) 99999-9999
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope mr-2 text-indigo-500"></i>
                            contato@oversizedfit.com.br
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-12 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 text-sm">© 2023 OversizedFit. Todos os direitos reservados.</p>
                <div class="flex space-x-4 mt-4 md:mt-0">
                    <a href="#" class="text-gray-400 hover:text-indigo-500 text-sm">Termos de Serviço</a>
                    <a href="#" class="text-gray-400 hover:text-indigo-500 text-sm">Política de Privacidade</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Floating WhatsApp Button -->
    <div class="fixed bottom-6 right-6 z-40">
        <a href="https://wa.me/5511999999999" class="bg-green-500 hover:bg-green-600 text-white rounded-full w-16 h-16 flex items-center justify-center shadow-xl floating">
            <i class="fab fa-whatsapp text-3xl"></i>
        </a>
    </div>

    <script>
        // Mobile menu toggle
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        
        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
                
                // Close mobile menu if open
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
            });
        });
    </script>
</body>
</html>
