<svg width="600" height="250" viewBox="0 0 600 250" xmlns="http://www.w3.org/2000/svg">
    <!-- 
      Definições e Estilos
      - Importa a fonte 'Poppins' do Google Fonts.
      - Define estilos para o texto e as faces do cubo.
    -->
    <defs>
        <style>
            @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@600;700&amp;display=swap');
            .logo-text {
                font-family: 'Poppins', sans-serif;
                font-weight: 700;
                font-size: 100px;
                fill: #ffffff;
                letter-spacing: -2px;
            }
            .ia-text {
                font-family: 'Poppins', sans-serif;
                font-weight: 700;
                font-size: 50px;
                fill: #ffffff;
            }
        </style>
    </defs>

    <!-- Fundo (opcional, pode remover se quiser fundo transparente) -->
    <rect width="100%" height="100%" fill="#111827" />

    <!-- Texto "vibecod" -->
    <text x="20" y="165" class="logo-text">vibecod</text>

    <!-- 
      Cubo Isométrico para o "ia"
      - O cubo é desenhado com 3 polígonos para simular a perspetiva 3D.
      - As cores são baseadas no design anterior.
    -->
    <g id="ia-cube" transform="translate(420, 60)">
        <!-- Face Lateral (Direita) -->
        <polygon points="50,25 100,0 100,100 50,125" fill="#8B5CF6" stroke="#A78BFA" stroke-width="2"/>
        
        <!-- Face Superior -->
        <polygon points="50,25 100,0 50,-25 0,0" fill="#A78BFA" stroke="#C4B5FD" stroke-width="2"/>
        
        <!-- Face Frontal -->
        <polygon points="0,0 50,25 50,125 0,100" fill="#C4B5FD" stroke="#DDD6FE" stroke-width="2"/>

        <!-- Texto "ia" posicionado na face frontal com uma leve inclinação -->
        <text x="12" y="85" class="ia-text" transform="skewY(-15)">ia</text>
    </g>
</svg>
