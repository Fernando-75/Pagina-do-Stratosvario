<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stratosvario_box: A Vanguarda da Decisão em Voo Livre</title>
    <style>
        :root {
            --primary-color: #007BFF;
            --secondary-color: #dc3545;
            --background-light: #f4f4f4;
            --background-dark: #333;
            --text-light: #fff;
            --text-dark: #333;
        }

        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--background-light);
            color: var(--text-dark);
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        .hero {
            background-color: var(--primary-color);
            color: var(--text-light);
            padding: 80px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            font-weight: 800;
        }
        .hero p {
            font-size: 1.2em;
            margin-bottom: 40px;
            opacity: 0.9;
        }

        .hero-highlight {
            font-size: 1.5em;
            font-weight: bold;
            display: block;
            margin-bottom: 30px;
            padding: 10px;
            background-color: var(--secondary-color);
            border-radius: 5px;
            color: var(--text-light);
        }

        .btn-cta {
            background-color: #28a745;
            color: var(--text-light);
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.2em;
            font-weight: bold;
            border-radius: 8px;
            transition: background-color 0.3s;
        }

        .btn-cta:hover {
            background-color: #1e7e34;
        }

        .section {
            padding: 60px 20px;
            border-bottom: 1px solid #ddd;
        }

        .section:nth-child(even) {
            background-color: var(--background-light);
        }

        .section h2 {
            font-size: 2em;
            color: var(--primary-color);
            margin-bottom: 40px;
            text-align: center;
            border-bottom: 2px solid var(--primary-color);
            display: inline-block;
            padding-bottom: 5px;
            width: 100%;
        }

        .feature-box {
            display: flex;
            gap: 30px;
            margin-top: 20px;
            flex-wrap: wrap;
            align-items: stretch;
        }

        .feature-item {
            flex: 1;
            min-width: 250px;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #eee;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        }

        .feature-item h3 {
            color: var(--secondary-color);
            margin-top: 0;
        }
        
        .image-placeholder {
            text-align: center;
            margin: 40px 0;
            padding: 20px;
            background-color: #eee;
            border-radius: 8px;
            border: 2px dashed #ccc;
        }
        
        .demo-section {
            background-color: #e0f7fa;
        }
        .demo-item {
            background-color: #fff; 
            border-color: var(--primary-color); 
            border-width: 2px; 
            border-style: solid;
        }


        .specs-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 30px;
        }

        .specs-table th, .specs-table td {
            border: 1px solid #ccc;
            padding: 12px;
            text-align: left;
        }

        .specs-table th {
            background-color: var(--primary-color);
            color: var(--text-light);
            width: 30%;
        }

        .cta-final {
            text-align: center;
            padding: 50px 20px;
            background-color: var(--background-dark);
            color: var(--text-light);
        }

        .cta-final h2 {
            color: #ffe400; 
            border-bottom: none;
        }
    </style>
</head>
<body>

    <header class="hero">
        <div class="container">
            <h1>Stratosvario_box: A Vanguarda da Decisão em Voo Livre.</h1>
            <p>Chegou a hora de voar com a precisão que só a inteligência artificial e o baixo ruído podem oferecer.</p>
            <span class="hero-highlight">0% Ruído. 100% Confiança. Filtro StratosSense AI Ativo.</span>
            <a href="#buy" class="btn-cta">Comprar Agora / Reserve o Seu</a>
        </div>
    </header>

    <main>
        <section class="section" id="product-gallery" style="padding-top: 30px; padding-bottom: 30px; background-color: #fff;">
            <div class="container" style="text-align: center;">
                <div class="feature-box" style="justify-content: center;">
                    <div style="flex: 0 0 30%; max-width: 250px; margin: 10px; border: 1px solid #ccc; padding: 10px;">
                        <p style="margin: 0; font-weight: bold;">Stratosvario na Mão</p>
                        <img src="foto1.png" alt="Stratosvario na palma da mão" style="width: 100%; height: auto; display: block; margin-top: 10px; border-radius: 4px;">
                    </div>
                    <div style="flex: 0 0 30%; max-width: 250px; margin: 10px; border: 1px solid #ccc; padding: 10px;">
                        <p style="margin: 0; font-weight: bold;">Detalhe do Buzzer</p>
                        <img src="foto2.png" alt="Detalhe do buzzer de alta performance" style="width: 100%; height: auto; display: block; margin-top: 10px; border-radius: 4px;">
                    </div>
                    <div style="flex: 0 0 30%; max-width: 250px; margin: 10px; border: 1px solid #ccc; padding: 10px;">
                        <p style="margin: 0; font-weight: bold;">Placa e Conectores</p>
                        <img src="foto3.png" alt="Visão interna da placa e conectores USB-C" style="width: 100%; height: auto; display: block; margin-top: 10px; border-radius: 4px;">
                    </div>
                </div>
            </div>
        </section>
        <section class="section" style="padding-top: 20px; padding-bottom: 20px; background-color: #fff;">
            <div class="container" style="text-align: center;">
                <a href="https://youtu.be/CZtDT3rveF4" target="_blank" style="text-decoration: none;">
                    <div style="background-color: var(--secondary-color); color: var(--text-light); padding: 15px; border-radius: 8px; font-size: 1.2em; font-weight: bold;">
                        ▶️ ASSISTA AO VÍDEO DE DEMONSTRAÇÃO COMPLETA
                    </div>
                </a>
            </div>
        </section>
        <section class="section">
            <div class="container">
                <h2>🧠 RECURSO CENTRAL: O FILTRO STRATOSSENSE AI & COCHLEAR</h2>

                <p style="font-size: 1.1em; line-height: 1.6;">
                    Desenhado para eliminar o ruído turbulento de borda de térmica e a trepidação, o Stratosvario\_box utiliza um algoritmo de **Inteligência Artificial (AI) proprietário** que atua como um filtro adaptativo.
                </p>
                
                <div class="image-placeholder">
                     Gráfico Comparando Linha Suja (BMP280) vs. Linha Limpa (DPS310 + AI)
                </div>

                <div class="feature-box">
                    <div class="feature-item">
                        <h3>Filtro Coclear (Zero Fadiga e Alto Desempenho)</h3>
                        <p>O Filtro Coclear simula o processamento do ouvido humano, concentrando-se na detecção de padrões reais e ignorando as altas frequências da turbulência. **Enquanto variômetros comuns adicionam mais de 1.2 segundos de lag com filtros de software**, nossa abordagem garante uma resposta quase instantânea, com um lag mínimo **inferior a 0.02 segundos**.</p>
                        <p>Isso significa que você escuta a térmica no momento exato em que a cruza, eliminando a confusão e a fadiga auditiva. **O som do seu vário nunca foi tão limpo e imediato.**</p>
                    </div>
                    <div class="feature-item">
                        <h3>Adaptação Dinâmica</h3>
                        <p>O StratosSense AI **analisa a turbulência e a pureza da ascensão no ambiente de voo atual**, adaptando instantaneamente a suavização. Garante máxima sensibilidade no ar calmo e a estabilidade necessária no núcleo da térmica.</p>
                    </div>
                    <div class="feature-item">
                        <h3>Modo Profissional</h3>
                        <p>Mantenha o filtro AI desligado e ajuste a **Suavização Manual de 0 a 10** (0 = Rápido / 10 = Lento) através da interface web para controle total sobre a filtragem.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="section">
            <div class="container">
                <h2>⚙️ TECNOLOGIA E PERFORMANCE</h2>

                <div class="feature-box">
                    <div class="feature-item">
                        <h3>CONCEITO BOX MODULAR E ULTRAFINO</h3>
                        <p>O Stratosvario\_box foi concebido com uma **espessura de apenas 13mm** (11cm C x 8cm L), otimizado para ser **colado com velcro diretamente ao seu celular ou tablet**. Isso cria um único aparelho, ultrafino, que ocupa o mínimo de espaço no porta-instrumentos.</p>
                        <p style="font-weight: bold; color: var(--primary-color);">Garante facilidade na troca da tela (celular/tablet) e total liberdade para migrar para um aparelho maior, sem trocar seu vário.</p>
                    </div>
                    <div class="feature-item">
                        <h3>Sensor DPS310 (Baixo Ruído)</h3>
                        <p>Comparado aos sensores BMP280, o DPS310 oferece **maior precisão** (**2cm de precisão** contra **10cm** dos filtros usados no mercado) e, crucialmente, um **ruído muito mais baixo**. Isso se traduz em bipes iniciais mais rápidos e informações mais limpas para o Filtro AI processar.</p>
                    </div>
                    <div class="feature-item">
                        <h3>Processador Dual Core</h3>
                        <p>Equipado com o microprocessador **Tensilica Xtensa LX6 Dual Core**, que oferece o desempenho necessário para executar o Filtro AI, o processamento do sensor DPS310 e a transmissão BLE simultaneamente.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="section demo-section">
            <div class="container">
                <h2>💻 DEMONSTRAÇÃO INTERATIVA: A SUA CENTRAL DE COMANDO</h2>
                <p style="font-size: 1.2em; margin-bottom: 30px;">
                    Experimente a facilidade e o controle de configurar seu Stratosvario\_box via Wi-Fi, sem a necessidade de instalar aplicativos.
                </p>
                <div class="feature-box">
                    <a href="config.html" target="_blank" style="text-decoration: none; flex: 1;">
                        <div class="feature-item demo-item">
                            <h3>VER CONFIGURAÇÕES PRINCIPAIS</h3>
                            <p>Simule o ajuste de perfis, gatilhos de subida/descida e a ativação dos Filtros AI e Manual.</p>
                            <span style="display: block; color: var(--primary-color); font-weight: bold;">(Abrir Interface)</span>
                        </div>
                    </a>
                    <a href="estudio_som.html" target="_blank" style="text-decoration: none; flex: 1;">
                        <div class="feature-item demo-item">
                            <h3>ACESSAR ESTÚDIO DE SOM</h3>
                            <p>Ajuste milissegundo a milissegundo a curva de áudio para criar um som único e perfeito para você.</p>
                            <span style="display: block; color: var(--primary-color); font-weight: bold;">(Abrir Estúdio)</span>
                        </div>
                    </a>
                </div>
            </div>
        </section>
        <section class="section">
            <div class="container">
                <h2>🔊 CONTROLE DE ÁUDIO E CUSTOMIZAÇÃO</h2>
                <p>O som é a sua segunda visão. Personalize cada detalhe da sua experiência sonora para máxima eficiência no voo.</p>

                <div class="feature-box">
                    <div class="feature-item">
                        <h3>Estúdio de Som Integrado</h3>
                        <p>Ajuste milissegundo a milissegundo a duração do **beep** e do **silêncio** para cada etapa da razão de subida **um nível interpolável** através da interface Wi-Fi dedicada. Nunca mais voe com um vário que você não pode calibrar.</p>
                    </div>
                    <div class="feature-item">
                        <h3>Perfis de Áudio Selecionáveis</h3>
                        <ul>
                            <li>**Stratos Dinâmico (Recomendado):** Curva profissional ajustável.</li>
                            <li>**Clássico Suave:** Curva linear padrão para familiarização.</li>
                            <li>**Modo Iniciante:** Limiares mais altos para evitar sobrecarga de informação.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section class="section" id="specs">
            <div class="container">
                <h2>🛠️ ESPECIFICAÇÕES TÉCNICAS</h2>
                <table class="specs-table">
                    <tr><th>Processador</th><td>Tensilica Xtensa LX6 Dual Core</td></tr>
                    <tr><th>Sensor Altimétrico</th><td>Adafruit DPS310 (Baixo Ruído, Precisão de 2cm)</td></tr>
                    <tr><th>Comunicação</th><td>Bluetooth Low Energy (BLE) / Wi-Fi (Configuração Web)</td></tr>
                    <tr><th>Protocolo de Saída</th><td>LK8EX1 (Compatível com XCTrack, XCSoar, etc.)</td></tr>
                    <tr><th>Dimensões (LxCxE)</th><td>8 cm x 11 cm x 13 mm (Design Modular Ultrafino)</td></tr> 
                    <tr><th>Autonomia (BLE Ativo)</th><td>15 - 19 horas contínuas (com bateria de 1100 mAh)</td></tr>
                    <tr><th>Carregamento</th><td>USB-C (Carregamento Universal 5V)</td></tr>
                    <tr><th>Modo Repouso</th><td>Consumo Ultrabaixo (Deep Sleep)</td></tr>
                </table>
            </div>
        </section>
    </main>

    <footer class="cta-final" id="buy">
        <div class="container">
            <h2>🔥 OFERTA DE LANÇAMENTO EXCLUSIVA! 🔥</h2>
            <p style="font-size: 1.5em; margin-bottom: 20px; font-weight: bold;">
                De R$ 400,00 por apenas: <span style="color: var(--primary-color); text-decoration: line-through;">R$ 400,00</span>
            </p>
            <p style="font-size: 2.2em; font-weight: 800; color: #ffe400; margin-top: -15px; margin-bottom: 30px;">
                R$ 250,00
            </p>
            
            <p style="font-size: 1.2em; margin-bottom: 30px;">
                Garanta o seu Stratosvario\_box e eleve a precisão do seu voo.
            </p>
            
            <a href="https://api.whatsapp.com/send?phone=5532999417780&text=Ol%C3%A1%2C%20gostaria%20de%20reservar%20o%20meu%20Stratosvario_box%20pelo%20pre%C3%A7o%20de%20lan%C3%A7amento%20de%20R%24250%2C00." target="_blank" class="btn-cta">
                RESERVAR AGORA VIA WHATSAPP
            </a>

            <p style="font-size: 0.9em; margin-top: 15px;">(Fale diretamente com o desenvolvedor: 32 9 9941-7780)</p>
        </div>
    </footer>

</body>
</html>
