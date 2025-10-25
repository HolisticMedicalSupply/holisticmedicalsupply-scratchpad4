<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complete Business Portfolio - Multi-Language</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; line-height: 1.6; color: #333; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 20px; }
        .container { max-width: 1600px; margin: 0 auto; background: white; border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
        
        .language-toggle { 
            position: sticky; 
            top: 0; 
            z-index: 1000; 
            background: rgba(255,255,255,0.98); 
            padding: 15px 40px; 
            display: flex; 
            justify-content: center; 
            gap: 15px; 
            border-bottom: 3px solid #667eea;
            box-shadow: 0 3px 15px rgba(0,0,0,0.1);
        }
        .lang-btn { 
            padding: 12px 30px; 
            border: 2px solid #667eea; 
            background: white; 
            color: #667eea; 
            border-radius: 8px; 
            cursor: pointer; 
            font-size: 1.1em; 
            font-weight: bold; 
            transition: all 0.3s ease;
        }
        .lang-btn:hover { background: #f0f0ff; transform: translateY(-2px); }
        .lang-btn.active { background: #667eea; color: white; }
        
        .lang-content { display: none; }
        .lang-content.active { display: block; }
        
        .header { background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%); color: white; padding: 60px 40px; text-align: center; }
        .header h1 { font-size: 4em; margin-bottom: 20px; }
        .success-banner { background: #27ae60; color: white; padding: 40px; text-align: center; font-size: 1.5em; font-weight: bold; }
        .section { padding: 50px 40px; }
        .section:nth-child(even) { background: #f8f9fa; }
        .section-title { font-size: 2.5em; color: #1e3c72; margin-bottom: 30px; text-align: center; border-bottom: 4px solid #667eea; padding-bottom: 15px; }
        .strategy-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(400px, 1fr)); gap: 30px; margin: 40px 0; }
        .strategy-card { background: white; border-radius: 15px; padding: 30px; box-shadow: 0 8px 25px rgba(0,0,0,0.1); border-top: 6px solid; transition: transform 0.3s ease; }
        .strategy-card:hover { transform: translateY(-10px); box-shadow: 0 15px 40px rgba(0,0,0,0.2); }
        .strategy-card h3 { font-size: 1.6em; margin-bottom: 15px; }
        .revenue-highlight { background: #27ae60; color: white; padding: 12px; border-radius: 8px; margin: 15px 0; text-align: center; font-size: 1.2em; font-weight: bold; }
        .view-link { display: block; background: linear-gradient(135deg, #667eea, #764ba2); color: white; text-align: center; padding: 12px; border-radius: 8px; text-decoration: none; font-weight: bold; margin-top: 15px; }
        .view-link:hover { background: linear-gradient(135deg, #764ba2, #667eea); }
        .badge { display: inline-block; padding: 5px 12px; border-radius: 15px; font-size: 0.8em; font-weight: bold; margin: 5px; }
        .badge.updated { background: #27ae60; color: white; }
        .stats-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin: 30px 0; }
        .stat-box { background: linear-gradient(135deg, #667eea, #764ba2); color: white; padding: 30px; border-radius: 15px; text-align: center; }
        .stat-number { font-size: 3em; font-weight: bold; display: block; margin-bottom: 10px; }
        .footer { background: linear-gradient(135deg, #1e3c72, #2a5298); color: white; padding: 50px 40px; text-align: center; }
    </style>
</head>
<body>
    <div class="container">
        <div class="language-toggle">
            <button class="lang-btn active" onclick="switchLanguage('en')" data-lang="en">🇺🇸 English</button>
            <button class="lang-btn" onclick="switchLanguage('ru')" data-lang="ru">🇷🇺 Русский</button>
            <button class="lang-btn" onclick="switchLanguage('uz')" data-lang="uz">🇺🇿 O'zbek</button>
        </div>

        <!-- ENGLISH -->
        <div class="lang-content active" id="content-en">
            <div class="header">
                <h1>✅ COMPLETE PORTFOLIO</h1>
                <p style="font-size: 1.8em;">All Strategies UPDATED with 36 BOC-Licensed Products</p>
            </div>

            <div class="success-banner">
                ✅ ALL 11 STRATEGIES: Licensed DME Equipment (70-80%) + Complementary Products (20-30%)
            </div>

            <div class="section">
                <h2 class="section-title">🎯 Core Documents</h2>
                <div class="strategy-grid">
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <span class="badge updated">UPDATED</span>
                        <h3>📊 Revenue Projections Summary</h3>
                        <p>Complete financial breakdown with all 36 BOC codes</p>
                        <div class="revenue-highlight">Year 1: $2.8M - $5.9M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad5/" class="view-link">View Revenue Summary →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <h3>🏥 DME Product Portfolio</h3>
                        <p>All 36 BOC categories with pricing and revenue estimates</p>
                        <div class="revenue-highlight">36 BOC Categories</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad6/" class="view-link">View Portfolio →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #f39c12;">
                        <h3>💰 Pricing Strategy & Market Positioning</h3>
                        <p>4-Tier pricing model: Economy, Value, US-Made, Luxury</p>
                        <div class="revenue-highlight">Market Strategy</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad7/" class="view-link">View Pricing Strategy →</a>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">📈 Financial Overview</h2>
                <div class="stats-grid">
                    <div class="stat-box"><span class="stat-number">36</span><span>BOC Categories</span></div>
                    <div class="stat-box"><span class="stat-number">11</span><span>Strategies</span></div>
                    <div class="stat-box"><span class="stat-number">$2.8-5.9M</span><span>Year 1 Target</span></div>
                    <div class="stat-box"><span class="stat-number">70-80%</span><span>DME Revenue</span></div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🎯 All 11 Strategies</h2>
                <div class="strategy-grid">
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <h3>🚨 1. Emergency Hospital Delivery</h3>
                        <p>2-4 hour guaranteed delivery to hospitals</p>
                        <div class="revenue-highlight">$560K - $1.6M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad8/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #27ae60;">
                        <h3>⛳ 2. Golf Course Programs</h3>
                        <p>Medical supply stations at golf courses</p>
                        <div class="revenue-highlight">$280K - $700K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad9/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #e67e22;">
                        <h3>🛡️ 3. Resilient Medical Supply</h3>
                        <p>Emergency preparedness market</p>
                        <div class="revenue-highlight">$500K - $1.0M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad10/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #9b59b6;">
                        <h3>🔄 4. Equipment Rental Programs</h3>
                        <p>Monthly recurring revenue model</p>
                        <div class="revenue-highlight">$600K - $1.1M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad11/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <h3>🏢 5. Facility Storage Cabinets</h3>
                        <p>B2B facility stocking programs</p>
                        <div class="revenue-highlight">$450K - $1.05M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad12/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #1abc9c;">
                        <h3>💻 6. Telehealth E-Commerce</h3>
                        <p>24/7 online DME store</p>
                        <div class="revenue-highlight">$900K - $1.8M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad13/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <h3>💊 7. Pharmacy Partnerships</h3>
                        <p>DME through pharmacy networks</p>
                        <div class="revenue-highlight">$280K - $700K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad14/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #f39c12;">
                        <h3>🎯 8. Specialty Divisions</h3>
                        <p>Pediatric • Veteran • Cancer • Bariatric • Pet</p>
                        <div class="revenue-highlight">$750K - $1.5M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad15/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #16a085;">
                        <h3>🔧 9. Home Modification Services</h3>
                        <p>Professional installation services</p>
                        <div class="revenue-highlight">$250K - $550K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad16/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #8e44ad;">
                        <h3>📱 10. Virtual Care Services</h3>
                        <p>Telehealth consultations & monitoring</p>
                        <div class="revenue-highlight">$350K - $700K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad17/" class="view-link">View Strategy →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #34495e;">
                        <h3>📦 11. General Product Lines</h3>
                        <p>ALL 36 BOC categories - foundation</p>
                        <div class="revenue-highlight">$1.2M - $2.3M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad18/" class="view-link">View Strategy →</a>
                    </div>
                </div>
            </div>

            <div class="footer">
                <h3 style="font-size: 3em;">✅ COMPLETE PORTFOLIO</h3>
                <p style="font-size: 3em; font-weight: bold; margin: 40px 0;">$2.8M - $5.9M</p>
                <p style="font-size: 1.3em;">Year 1 Target (4 Core Strategies)</p>
            </div>
        </div>

        <!-- RUSSIAN -->
        <div class="lang-content" id="content-ru">
            <div class="header">
                <h1>✅ ПОЛНОЕ ПОРТФОЛИО</h1>
                <p style="font-size: 1.8em;">Все Стратегии с 36 Лицензированными BOC Продуктами</p>
            </div>

            <div class="success-banner">
                ✅ ВСЕ 11 СТРАТЕГИЙ: Лицензированное DME (70-80%) + Дополнительные Продукты (20-30%)
            </div>

            <div class="section">
                <h2 class="section-title">🎯 Основные Документы</h2>
                <div class="strategy-grid">
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <span class="badge updated">ОБНОВЛЕНО</span>
                        <h3>📊 Сводка Прогнозов Доходов</h3>
                        <p>Полная финансовая разбивка со всеми 36 кодами BOC</p>
                        <div class="revenue-highlight">1-й Год: $2.8M - $5.9M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad5/" class="view-link">Посмотреть Сводку →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <h3>🏥 Портфолио DME Продуктов</h3>
                        <p>Все 36 категорий BOC с ценами и оценками доходов</p>
                        <div class="revenue-highlight">36 Категорий BOC</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad6/" class="view-link">Посмотреть Портфолио →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #f39c12;">
                        <h3>💰 Ценовая Стратегия и Позиционирование</h3>
                        <p>4-уровневая модель: Эконом, Ценность, США, Люкс</p>
                        <div class="revenue-highlight">Рыночная Стратегия</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad7/" class="view-link">Посмотреть Стратегию →</a>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">📈 Финансовый Обзор</h2>
                <div class="stats-grid">
                    <div class="stat-box"><span class="stat-number">36</span><span>Категорий BOC</span></div>
                    <div class="stat-box"><span class="stat-number">11</span><span>Стратегий</span></div>
                    <div class="stat-box"><span class="stat-number">$2.8-5.9M</span><span>Цель на 1-й Год</span></div>
                    <div class="stat-box"><span class="stat-number">70-80%</span><span>Доход от DME</span></div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🎯 Все 11 Стратегий</h2>
                <div class="strategy-grid">
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <h3>🚨 1. Экстренная Больничная Доставка</h3>
                        <p>Гарантированная доставка 2-4 часа</p>
                        <div class="revenue-highlight">$560K - $1.6M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad8/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #27ae60;">
                        <h3>⛳ 2. Программы Гольф-Клубов</h3>
                        <p>Медицинские станции на полях для гольфа</p>
                        <div class="revenue-highlight">$280K - $700K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad9/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #e67e22;">
                        <h3>🛡️ 3. Устойчивые Медицинские Поставки</h3>
                        <p>Рынок готовности к чрезвычайным ситуациям</p>
                        <div class="revenue-highlight">$500K - $1.0M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad10/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #9b59b6;">
                        <h3>🔄 4. Программы Аренды Оборудования</h3>
                        <p>Модель ежемесячных повторяющихся доходов</p>
                        <div class="revenue-highlight">$600K - $1.1M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad11/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <h3>🏢 5. Складские Шкафы для Учреждений</h3>
                        <p>Программы складирования B2B</p>
                        <div class="revenue-highlight">$450K - $1.05M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad12/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #1abc9c;">
                        <h3>💻 6. Телемедицина и Электронная Коммерция</h3>
                        <p>Онлайн-магазин DME 24/7</p>
                        <div class="revenue-highlight">$900K - $1.8M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad13/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <h3>💊 7. Партнерства с Аптеками</h3>
                        <p>DME через аптечные сети</p>
                        <div class="revenue-highlight">$280K - $700K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad14/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #f39c12;">
                        <h3>🎯 8. Специализированные Подразделения</h3>
                        <p>Педиатрия • Ветераны • Онкология • Бариатрия • Животные</p>
                        <div class="revenue-highlight">$750K - $1.5M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad15/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #16a085;">
                        <h3>🔧 9. Услуги по Модификации Домов</h3>
                        <p>Профессиональные услуги по установке</p>
                        <div class="revenue-highlight">$250K - $550K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad16/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #8e44ad;">
                        <h3>📱 10. Услуги Виртуальной Помощи</h3>
                        <p>Телемедицинские консультации и мониторинг</p>
                        <div class="revenue-highlight">$350K - $700K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad17/" class="view-link">Посмотреть →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #34495e;">
                        <h3>📦 11. Общие Линейки Продуктов</h3>
                        <p>ВСЕ 36 категорий BOC - основа</p>
                        <div class="revenue-highlight">$1.2M - $2.3M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad18/" class="view-link">Посмотреть →</a>
                    </div>
                </div>
            </div>

            <div class="footer">
                <h3 style="font-size: 3em;">✅ ПОЛНОЕ ПОРТФОЛИО</h3>
                <p style="font-size: 3em; font-weight: bold; margin: 40px 0;">$2.8M - $5.9M</p>
                <p style="font-size: 1.3em;">Цель на 1-й Год (4 Основные Стратегии)</p>
            </div>
        </div>

        <!-- UZBEK -->
        <div class="lang-content" id="content-uz">
            <div class="header">
                <h1>✅ TO'LIQ PORTFEL</h1>
                <p style="font-size: 1.8em;">36 BOC Litsenziyalangan Mahsulotlar bilan Barcha Strategiyalar</p>
            </div>

            <div class="success-banner">
                ✅ BARCHA 11 STRATEGIYA: Litsenziyalangan DME (70-80%) + Qo'shimcha Mahsulotlar (20-30%)
            </div>

            <div class="section">
                <h2 class="section-title">🎯 Asosiy Hujjatlar</h2>
                <div class="strategy-grid">
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <span class="badge updated">YANGILANGAN</span>
                        <h3>📊 Daromad Prognozlari Xulosasi</h3>
                        <p>Barcha 36 BOC kodlari bilan to'liq moliyaviy taqsimot</p>
                        <div class="revenue-highlight">1-Yil: $2.8M - $5.9M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad5/" class="view-link">Xulosani Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <h3>🏥 DME Mahsulot Portfeli</h3>
                        <p>Narxlar va daromad taxminlari bilan barcha 36 BOC toifalari</p>
                        <div class="revenue-highlight">36 BOC Toifalari</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad6/" class="view-link">Portelni Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #f39c12;">
                        <h3>💰 Narx Strategiyasi va Bozor Joylashuvi</h3>
                        <p>4 darajali model: Iqtisodiy, Qiymat, AQSH, Hashamat</p>
                        <div class="revenue-highlight">Bozor Strategiyasi</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad7/" class="view-link">Strategiyani Ko'rish →</a>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">📈 Moliyaviy Sharh</h2>
                <div class="stats-grid">
                    <div class="stat-box"><span class="stat-number">36</span><span>BOC Toifalari</span></div>
                    <div class="stat-box"><span class="stat-number">11</span><span>Strategiyalar</span></div>
                    <div class="stat-box"><span class="stat-number">$2.8-5.9M</span><span>1-Yil Maqsadi</span></div>
                    <div class="stat-box"><span class="stat-number">70-80%</span><span>DME Daromadi</span></div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">🎯 Barcha 11 Strategiya</h2>
                <div class="strategy-grid">
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <h3>🚨 1. Shoshilinch Kasalxona Yetkazib Berish</h3>
                        <p>2-4 soat kafolatlangan yetkazib berish</p>
                        <div class="revenue-highlight">$560K - $1.6M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad8/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #27ae60;">
                        <h3>⛳ 2. Golf Klub Dasturlari</h3>
                        <p>Golf maydonlarida tibbiy ta'minot stansiyalari</p>
                        <div class="revenue-highlight">$280K - $700K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad9/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #e67e22;">
                        <h3>🛡️ 3. Chidamli Tibbiy Ta'minot</h3>
                        <p>Favqulodda vaziyatlarga tayyorgarlik bozori</p>
                        <div class="revenue-highlight">$500K - $1.0M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad10/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #9b59b6;">
                        <h3>🔄 4. Uskuna Ijara Dasturlari</h3>
                        <p>Oylik takrorlanuvchi daromad modeli</p>
                        <div class="revenue-highlight">$600K - $1.1M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad11/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <h3>🏢 5. Muassasalar Saqlash Shkaflar</h3>
                        <p>B2B muassasalar saqlash dasturlari</p>
                        <div class="revenue-highlight">$450K - $1.05M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad12/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #1abc9c;">
                        <h3>💻 6. Teletibbiyot va Elektron Tijorat</h3>
                        <p>24/7 onlayn DME do'koni</p>
                        <div class="revenue-highlight">$900K - $1.8M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad13/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <h3>💊 7. Dorixonalar bilan Hamkorlik</h3>
                        <p>Dorixona tarmoqlari orqali DME</p>
                        <div class="revenue-highlight">$280K - $700K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad14/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #f39c12;">
                        <h3>🎯 8. Maxsus Bo'limlar</h3>
                        <p>Pediatriya • Faxriylar • Saraton • Bariatrik • Hayvonlar</p>
                        <div class="revenue-highlight">$750K - $1.5M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad15/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #16a085;">
                        <h3>🔧 9. Uy Modifikatsiyasi Xizmatlari</h3>
                        <p>Professional o'rnatish xizmatlari</p>
                        <div class="revenue-highlight">$250K - $550K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad16/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #8e44ad;">
                        <h3>📱 10. Virtual Tibbiy Xizmatlar</h3>
                        <p>Teletibbiy maslahatlari va monitoring</p>
                        <div class="revenue-highlight">$350K - $700K</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad17/" class="view-link">Ko'rish →</a>
                    </div>

                    <div class="strategy-card" style="border-top-color: #34495e;">
                        <h3>📦 11. Umumiy Mahsulot Liniyalari</h3>
                        <p>BARCHA 36 BOC toifalari - asos</p>
                        <div class="revenue-highlight">$1.2M - $2.3M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad18/" class="view-link">Ko'rish →</a>
                    </div>
                </div>
            </div>

            <div class="footer">
                <h3 style="font-size: 3em;">✅ TO'LIQ PORTFEL</h3>
                <p style="font-size: 3em; font-weight: bold; margin: 40px 0;">$2.8M - $5.9M</p>
                <p style="font-size: 1.3em;">1-Yil Maqsadi (4 Asosiy Strategiya)</p>
            </div>
        </div>
    </div>

    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.lang-content').forEach(content => content.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(btn => btn.classList.remove('active'));
            document.getElementById('content-' + lang).classList.add('active');
            document.querySelector(`.lang-btn[data-lang="${lang}"]`).classList.add('active');
            localStorage.setItem('preferred-language', lang);
            window.scrollTo(0, 0);
        }
        window.addEventListener('DOMContentLoaded', function() {
            const savedLang = localStorage.getItem('preferred-language');
            if (savedLang && ['en', 'ru', 'uz'].includes(savedLang)) switchLanguage(savedLang);
        });
    </script>
</body>
</html>
