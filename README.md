<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ensaios Não Destrutivos - Gabriel Costa Leao</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background: #f5f7fa;
      color: #333;
    }
    header {
      background: #1a202c;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .container {
      max-width: 900px;
      margin: auto;
      padding: 2rem;
      background: white;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      margin-top: -2rem;
      border-radius: 12px;
    }
    h2 {
      color: #2b6cb0;
      margin-top: 2rem;
    }
    ul {
      padding-left: 1.2rem;
    }
    .faq {
      margin-top: 2rem;
    }
    .faq dt {
      font-weight: 600;
      margin-top: 1rem;
    }
    .footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      color: #777;
    }
    .subsection {
      margin-top: 1rem;
      padding-left: 1rem;
    }
    img {
      width: 100%;
      max-width: 700px;
      display: block;
      margin: 1rem auto;
      border-radius: 8px;
      box-shadow: 0 0 6px rgba(0, 0, 0, 0.1);
    }
    figcaption {
      text-align: center;
      font-size: 0.9rem;
      color: #555;
      margin-bottom: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ensaios Não Destrutivos (END)</h1>
    <p>Detecção e Monitoramento de Falhas em Estruturas</p>
    <p><strong>Gabriel Costa Leao - Engenharia Civil | UNDB</strong></p>
  </header>

  <main class="container">
    <h2>Resumo do Trabalho</h2>
    <p>O trabalho analisa técnicas de Ensaios Não Destrutivos (END) aplicadas à engenharia civil e ao patrimônio histórico, com foco em métodos ópticos, acústicos, eletromagnéticos e físico-químicos. Explora-se ainda o uso da inteligência artificial e sensores modernos para melhorar a precisão e a eficiência da inspeção estrutural.</p>

    <h2>Objetivos</h2>
    <ul>
      <li>Compreender os diferentes métodos END e suas aplicações.</li>
      <li>Destacar os avanços com IA e aprendizado de máquina.</li>
      <li>Avaliar a eficácia dos END em estruturas históricas e de concreto armado.</li>
    </ul>

    <h2>Metodologia</h2>
    <p>Foi realizada uma revisão sistemática da literatura entre 2015 e 2025 em bases de dados técnicas. A análise crítica dos métodos considerou aplicabilidade, vantagens, limitações e estudos de caso reais.</p>

    <h2>Detalhamento dos Métodos</h2>
    <ul>
      <li><strong>Ópticos:</strong> Utilizam luz (laser, infravermelho) para mapear deformações e falhas superficiais. Técnicas como Interferometria, Shearografia e Termografia permitem detectar microfissuras e tensões internas sem contato físico direto. A ESPI, por exemplo, compara padrões de speckle antes e após estímulos na estrutura, revelando microdeformações.
        <figure>
          <img src="https://i.imgur.com/Sx3rDEy.png" alt="Esquema de interferometria óptica" />
          <figcaption>Figura 1 - Configuração óptica de interferometria (Fonte: adaptado de literatura técnica)</figcaption>
        </figure>
      </li>
      <li><strong>Acústicos:</strong> Empregam propagação de ondas sonoras. O UPV mede a velocidade do som no material para avaliar homogeneidade. O Impact-Echo gera um pulso de impacto e analisa os ecos refletidos para identificar delaminações internas. A Emissão Acústica detecta sinais gerados por microfraturas em tempo real.
        <figure>
          <img src="https://i.imgur.com/7BVGHPF.png" alt="Impact-Echo" />
          <figcaption>Figura 2 - Funcionamento do método Impact-Echo (Fonte: adaptado de Timcakova et al., 2015)</figcaption>
        </figure>
      </li>
      <li><strong>Eletromagnéticos:</strong> Envolvem interação com campos eletromagnéticos. O GPR emite ondas de rádio no solo ou estrutura e interpreta os reflexos para detectar anomalias. A Tomografia de Corrente Parasita (ECT) avalia descontinuidades em metais por meio da variação de correntes induzidas. Radiografia e Tomografia Computadorizada geram imagens detalhadas do interior das peças.
        <figure>
          <img src="https://i.imgur.com/8mKzXnJ.png" alt="Exemplo de radar GPR" />
          <figcaption>Figura 3 - Radar de Penetração no Solo (Fonte: adaptado de Oliveira et al., 2016)</figcaption>
        </figure>
      </li>
      <li><strong>Físico-Químicos:</strong> Avaliam propriedades mecânicas e químicas. O Martelo de Schmidt estima resistência do concreto por rebote. A análise de carbonatação e cloretos indica riscos de corrosão. A espectroscopia e a difração de raios X permitem identificar a composição e estrutura cristalina dos materiais.
        <figure>
          <img src="https://i.imgur.com/d8KJ3hb.jpg" alt="Martelo Schmidt em uso" />
          <figcaption>Figura 4 - Ensaio com Martelo de Schmidt (Fonte: Helene & Terzian, 1992)</figcaption>
        </figure>
      </li>
    </ul>

    <h2>Aplicações Práticas</h2>
    <ul>
      <li><strong>Patrimônio histórico:</strong> Diagnóstico sem dano a estruturas antigas (alvenaria, pedra).</li>
      <li><strong>Concreto armado:</strong> Monitoramento de corrosão, resistência, integridade estrutural.</li>
      <li><strong>Indústria e infraestrutura:</strong> Aeroespacial, rodovias, energia e offshore.</li>
    </ul>

    <h2>Integração com Inteligência Artificial</h2>
    <p>Modelos de machine learning auxiliam na interpretação de dados complexos, reduzindo erros humanos e antecipando falhas com precisão superior, especialmente em imagens de termografia, sinais acústicos e padrões ópticos.</p>

    <h2>FAQ - Perguntas Frequentes</h2>
    <dl class="faq">
      <dt>Por que escolheu esse tema?</dt>
      <dd>Porque une tecnologia, preservação e engenharia de forma inovadora e impactante para o futuro da construção civil.</dd>

      <dt>Qual a principal diferença entre os métodos ópticos e acústicos?</dt>
      <dd>Os ópticos analisam deformações na superfície via luz; os acústicos detectam falhas internas pela propagação de ondas.</dd>

      <dt>Qual método é mais indicado para estruturas históricas?</dt>
      <dd>Métodos ópticos e eletromagnéticos, como termografia e GPR, pois são não invasivos e sensíveis a microdanos.</dd>

      <dt>Como a IA contribui com os ENDs?</dt>
      <dd>Com algoritmos que aprendem padrões de falha, otimizam diagnósticos e reduzem erros operacionais.</dd>
    </dl>

    <h2>Referências Selecionadas</h2>
    <p>McCann & Forde (2001), Carino (2001), Maierhofer et al. (2007), Tortora et al. (2023), Zhang et al. (2024), entre outros.</p>

    <h2>Download do TCC Completo</h2>
    <p><a href="#">[Inserir link para PDF aqui]</a></p>
  </main>

  <footer class="footer">
    Página criada para fins acadêmicos - Gabriel Costa Leao | Engenharia Civil | UNDB - 2025
  </footer>
</body>
</html>
