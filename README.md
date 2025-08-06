# restaurgit branch -M main
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نسخة جديدة</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;900&display=swap');
        
        body {
            font-family: 'Tajawal', sans-serif;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        .transition-all {
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="gradient-bg text-white shadow-lg">
        <div class="container mx-auto px-4 py-6">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-4 space-x-reverse">
                    <div class="w-12 h-12 bg-white rounded-full flex items-center justify-center">
                        <i class="fas fa-rocket text-purple-700 text-xl"></i>
                    </div>
                    <h1 class="text-2xl font-bold">شركتنا</h1>
                </div>
                
                <nav class="hidden md:block">
                    <ul class="flex space-x-8 space-x-reverse">
                        <li><a href="#" class="hover:text-purple-200 transition-all">الرئيسية</a></li>
                        <li><a href="#" class="hover:text-purple-200 transition-all">من نحن</a></li>
                        <li><a href="#" class="hover:text-purple-200 transition-all">الخدمات</a></li>
                        <li><a href="#" class="hover:text-purple-200 transition-all">المشاريع</a></li>
                        <li><a href="#" class="hover:text-purple-200 transition-all">اتصل بنا</a></li>
                    </ul>
                </nav>
                
                <button class="md:hidden text-white focus:outline-none">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="gradient-bg text-white py-20">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold mb-6">حلول تقنية مبتكرة لعملك</h1>
                <p class="text-xl mb-8 leading-relaxed">نقدم أحدث الحلول التقنية التي تساعد عملك على النمو والازدهار في العصر الرقمي.</p>
                <div class="flex space-x-4 space-x-reverse">
                    <button class="bg-white text-purple-700 px-8 py-3 rounded-full font-bold hover:bg-purple-100 transition-all">
                        ابدأ الآن
                    </button>
                    <button class="border-2 border-white text-white px-8 py-3 rounded-full font-bold hover:bg-white hover:text-purple-700 transition-all">
                        اعرف المزيد
                    </button>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <img src="https://via.placeholder.com/600x400" alt="Hero Image" class="rounded-lg shadow-2xl w-full max-w-md">
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">مميزاتنا</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">نقدم مجموعة من الحلول التقنية المبتكرة التي تلبي جميع احتياجاتك</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Feature 1 -->
                <div class="bg-gray-50 p-8 rounded-xl card-hover transition-all">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-bolt text-purple-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-4">سرعة فائقة</h3>
                    <p class="text-gray-600">حلولنا تتميز بسرعة الأداء وكفاءة التشغيل لضمان تجربة مستخدم سلسة.</p>
                </div>
                
                <!-- Feature 2 -->
                <div class="bg-gray-50 p-8 rounded-xl card-hover transition-all">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-shield-alt text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-4">حماية متكاملة</h3>
                    <p class="text-gray-600">نوفر طبقات متعددة من الحماية لضمان أمان بياناتك وخصوصية عملائك.</p>
                </div>
                
                <!-- Feature 3 -->
                <div class="bg-gray-50 p-8 rounded-xl card-hover transition-all">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-headset text-green-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-4">دعم فني 24/7</h3>
                    <p class="text-gray-600">فريق الدعم الفني لدينا متاح على مدار الساعة لمساعدتك في أي وقت.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-20 bg-gray-100">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 text-center">
                <div class="bg-white p-8 rounded-xl shadow-sm">
                    <div class="text-5xl font-bold text-purple-600 mb-2">10K+</div>
                    <div class="text-gray-600">عملاء راضون</div>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-sm">
                    <div class="text-5xl font-bold text-blue-600 mb-2">15+</div>
                    <div class="text-gray-600">سنوات خبرة</div>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-sm">
                    <div class="text-5xl font-bold text-green-600 mb-2">500+</div>
                    <div class="text-gray-600">مشروع مكتمل</div>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-sm">
                    <div class="text-5xl font-bold text-yellow-600 mb-2">50+</div>
                    <div class="text-gray-600">جائزة وتكريم</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">آراء عملائنا</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">ما يقولونه عنا</p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-gray-50 p-8 rounded-xl border border-gray-200">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 rounded-full overflow-hidden mr-4">
                            <img src="https://via.placeholder.com/150" alt="Client" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-bold text-lg">أحمد محمد</h4>
                            <p class="text-gray-600">مدير شركة التقنية</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"لقد ساعدتنا هذه الشركة في تحويل أعمالنا إلى المنصة الرقمية باحترافية عالية. فريق العمل محترف ويقدم دعمًا ممتازًا."</p>
                    <div class="mt-4 text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-gray-50 p-8 rounded-xl border border-gray-200">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 rounded-full overflow-hidden mr-4">
                            <img src="https://via.placeholder.com/150" alt="Client" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-bold text-lg">سارة عبدالله</h4>
                            <p class="text-gray-600">رئيسة قسم التسويق</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"الحلول التي قدمتها لنا الشركة ساعدت في زيادة مبيعاتنا بنسبة 40% خلال ثلاثة أشهر فقط. أنصح الجميع بالتعامل معهم."</p>
                    <div class="mt-4 text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-gray-50 p-8 rounded-xl border border-gray-200">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 rounded-full overflow-hidden mr-4">
                            <img src="https://via.placeholder.com/150" alt="Client" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-bold text-lg">خالد سعيد</h4>
                            <p class="text-gray-600">مالك متجر إلكتروني</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"بعد تحويل متجري إلى منصة إلكترونية مع هذه الشركة، زادت مبيعاتي بشكل كبير وأصبح لدي عملاء من جميع أنحاء العالم."</p>
                    <div class="mt-4 text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20 gradient-bg text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">هل أنت مستعد لبدء مشروعك القادم؟</h2>
            <p class="text-xl mb-8 max-w-2xl mx-auto">اتصل بنا اليوم واحصل على استشارة مجانية من خبرائنا لتطوير عملك</p>
            <button class="bg-white text-purple-700 px-10 py-4 rounded-full font-bold hover:bg-purple-100 transition-all text-lg">
                تواصل معنا الآن
            </button>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white pt-16 pb-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-12 mb-12">
                <!-- Column 1 -->
                <div>
                    <div class="flex items-center space-x-4 space-x-reverse mb-6">
                        <div class="w-12 h-12 bg-white rounded-full flex items-center justify-center">
                            <i class="fas fa-rocket text-purple-700 text-xl"></i>
                        </div>
                        <h3 class="text-xl font-bold">شركتنا</h3>
                    </div>
                    <p class="text-gray-400 mb-6">نقدم حلولاً تقنية مبتكرة تساعد الشركات على النمو والازدهار في العصر الرقمي.</p>
                    <div class="flex space-x-4 space-x-reverse">
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-purple-600 transition-all">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-purple-600 transition-all">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-purple-600 transition-all">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-purple-600 transition-all">
                            <i class="fab fa-instagram"></i>
                        </a>
                    </div>
                </div>
                
                <!-- Column 2 -->
                <div>
                    <h4 class="text-lg font-bold mb-6">روابط سريعة</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">الرئيسية</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">من نحن</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">الخدمات</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">المشاريع</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">اتصل بنا</a></li>
                    </ul>
                </div>
                
                <!-- Column 3 -->
                <div>
                    <h4 class="text-lg font-bold mb-6">خدماتنا</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">تطوير الويب</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">تطبيقات الجوال</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">التسويق الرقمي</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">تصميم UI/UX</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-all">الاستضافة والسحابة</a></li>
                    </ul>
                </div>
                
                <!-- Column 4 -->
                <div>
                    <h4 class="text-lg font-bold mb-6">اتصل بنا</h4>
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt mt-1 mr-3 text-purple-500"></i>
                            <span class="text-gray-400">الرياض، المملكة العربية السعودية</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone mr-3 text-purple-500"></i>
                            <span class="text-gray-400">+966 12 345 6789</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope mr-3 text-purple-500"></i>
                            <span class="text-gray-400">info@example.com</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 mb-4 md:mb-0">© 2023 شركتنا. جميع الحقوق محفوظة.</p>
                <div class="flex space-x-6 space-x-reverse">
                    <a href="#" class="text-gray-400 hover:text-white transition-all">سياسة الخصوصية</a>
                    <a href="#" class="text-gray-400 hover:text-white transition-all">شروط الخدمة</a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.querySelector('button[class*="md:hidden"]').addEventListener('click', function() {
            // This would toggle a mobile menu in a real implementation
            alert('سيتم فتح قائمة الجوال هنا في التطبيق الكامل');
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Animation for cards on scroll
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('animate-fadeIn');
                }
            });
        }, { threshold: 0.1 });
        
        document.querySelectorAll('.card-hover').forEach(card => {
            observer.observe(card);
            card.classList.add('opacity-0', 'transition-all', 'duration-500');
        });
        
        // Add animation class when element is in view
        setTimeout(() => {
            document.querySelectorAll('.card-hover').forEach(card => {
                card.classList.add('animate-fadeIn');
                card.classList.remove('opacity-0');
            });
        }, 500);
    </script>
</body>
</html>
