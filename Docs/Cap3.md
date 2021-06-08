# 3. DESENVOLVIMENTO DO TRABALHO
Para este estudo serão explicados os conceitos básicos para o entendimento do projeto. Serão usadas as referências que foram revisadas no Capítulo anterior.
## 3.1. Metodologias de Treinamento
### 3.1.1. O que é Realidade Virtual

O termo "realidade virtual" foi originalmente cunhado por Jaron Lanier na década de 1980 para distinguir entre a simulação de computador tradicional e o ambiente cada vez mais imersivo que ele tentou desenvolver para a prática de exploração espacial. Porém, com o aumento da acessibilidade que o computador trouxe, a tecnologia de realidade virtual pôde ser incorporada ao mercado em massa e de entretenimento, como videogames e filmes, o que torna essa tecnologia acessível ao grande público. (Kuo, Levis, 2002).

De acordo com Bellalouna (2020) a realidade virtual (VR) é uma simulação de computador interativa que detecta o estado e a operação do usuário e substitui ou aprimora as informações de feedback sensorial de um ou mais sentidos, fazendo com que o usuário se sinta imerso na simulação. 

Geralmente, os dispositivos de realidade virtual usam um ou mais dos seguintes hardwares: uma única tela de projeção grande (Chamada VR Powerwall), várias telas de projeção conectadas (Chamada VR CAVE) ou um monitor estereoscópico com recursos de desktop e rastreamento de cabeça. (Visor do tipo head-mounted ou HMD).

Segundo Fogler (1995), em um mundo virtual ideal, o usuário seria completamente incapaz de determinar se está experimentando a simulação de computador ou realidade, a imersão seria completa e a experiência pessoal seria a mesma que sua experiência no mundo real.

Martins e Guimarães (2012) explicam que um ambiente virtual típico normalmente deve possuir certas características marcantes, dentre elas:
- Sintético: um sistema computacional gera o ambiente em tempo real, ou seja, ele não é pré-gravado
- Tridimensional: Devido a sua profundidade e tentativa de similaridade ao ambiente real, o ambiente virtual é normalmente representado tridimensionalmente para passar a sensação de realidade.
- Multisensorial: o sistema utiliza de sentido visual, sonoro, espacial, de reação do usuário com o ambiente, dentre outros, para estimular o cérebro a pensar que está em um ambiente real.
- Imersivo: É a exploração de vários sentidos para trazer a sensação que o usuário está dentro do ambiente produzido computacionalmente. Normalmente, um sistema totalmente imersivo é obtido com o uso de capacetes de visualização e CAVEs 
- Interativo: através dos comandos do usuário, o computador irá modificar o mundo virtual, realizando um feedback instantâneo.
- Realístico: O ambiente virtual normalmente tenta reproduzir objetos reais, ou sua interação com eles como gravidade, peso etc. com precisão.

### 3.1.2. O que é Realidade Aumentada

De acordo com Farkhatdinov e Ryu (2003), a realidade aumentada (AR) é um campo de pesquisa computacional que envolve a combinação do mundo real e dados gerados por computador (semelhante à realidade virtual), onde objetos gráficos de computador são combinados em imagens reais em tempo real. 

Bellalouna (2020) estabelece que o sistema de AR deve compreender o ambiente no qual deve aumentar, portanto, a câmera é usada para fornecer imagens do mundo real. As soluções de AR mais comuns usam apenas uma câmera, mas várias câmeras podem ser usadas, se necessário. Portanto, para combinar o mundo virtual com o mundo real, o movimento dos objetos nos dois mundos deve ser rastreado. Na RV tudo é criado manualmente para definir a localização dos objetos, enquanto na AR o sistema deve acompanhar as mudanças do mundo real para que o mundo virtual corresponda efetivamente à realidade. Por este motivo, diferentes tipos de rastreadores são usados: sistemas infravermelhos, mecânicos, inerciais, ultrassônicos, baseados em visão e híbridos. Cada tipo de rastreador possui diferentes condições de trabalho e é adequado para diferentes tipos de tarefas. O objetivo do rastreamento é fornecer alta precisão, baixa latência, baixo jitter e robustez. Após essas etapas, é necessário analisar todas as informações coletadas das câmeras e rastreadores, realizar o processamento dos dados e estimar a posição dos objetos no mundo real. Neste ponto, o sistema AR pode sobrepor corretamente objetos virtuais em imagens do mundo real, fornecendo aos usuários instruções úteis.

Segundo Martins e Guimarães (2012), existem três características principais nos
sistemas de RA:
- Combinação do mundo real com os objetos virtuais dentro do ambiente real;
- Interatividade em tempo real;
- Alinhamento exato dos objetos virtuais no ambiente real.

![Realidades](https://user-images.githubusercontent.com/64936673/121264431-7d1e1700-c88d-11eb-885d-0ea6374714d6.png)
<p align="center">
    Figura 1 - Realidades Aumentada, Mista e Virtual
</p>

### 3.1.3. Onde RV é aplicado?

As aplicações de Realidade Virtual têm sido bem relatadas em protótipos virtuais, em usinagem, montagem, diagnóstico e aprendizagem de falhas virtual baseados na web e vários outros tipos de operações de manufatura (Damiani et al, 2018).

Quanto ao âmbito educacional, Gavish et al. (2015) nos diz que em comparação com os sistemas de treinamento tradicionais, o treinamento usando a tecnologia de RV oferece uma série de benefícios. Quando as restrições impedem o uso de ambientes reais (como restrições de disponibilidade de máquina, segurança, tempo ou custo), os sistemas de RV podem fornecer pistas adicionais que não estão disponíveis no mundo real, que pode facilitar o aprendizado de tarefas (por exemplo, dicas visuais, auditivas ou táteis) e permitem a simulação de tarefas com flexibilidade para adaptá-las às necessidades e objetivos de treinamento do usuário.

Além disso, Kuo e Levis (2002) dizem que os alunos aprendem melhor em um ambiente construtivista porque participam dos materiais do curso tanto física quanto mentalmente. O método antigo de ensino "bancário" pressupõe que o professor detém todo o conhecimento, e quando ele "adquire" suas informações e as "armazena" na mente do aluno, o processo de aprendizagem será promovido. Em contraste, em um ambiente de aprendizagem centrado no aluno, os alunos são vistos como co-construtores do ambiente educacional. Essa abordagem inclusiva traz os alunos para os materiais do curso, tornando o conhecimento significativo e promovendo o aprendizado.

### 3.1.4. Onde RA é aplicado?

Uma das primeiras aplicações da tecnologia de realidade aumentada foi introduzida pela primeira vez por T. Caudell em 1992. Era usada para melhorar a eficiência e a qualidade dos trabalhadores humanos na execução de atividades de manufatura. A realidade aumentada rapidamente se tornou popular entre pesquisadores, engenheiros, designers, etc. Ela foi aplicada com sucesso em muitos campos, como robótica, medicina, engenharia automotiva e aeroespacial. (Farkhatdinov, Ryu, 2003).

Segundo Cardoso et al. (2014), algumas das áreas de utilização da Realidade Aumentada estão o treinamento a tarefas complexas, visualização de elementos construtivos a inserção de ambientes reais em engenharias, mapeamento de dados por estimativa em ambientes reais visualização de dados, com o objetivo de aprimoramento, simulações, entretenimento, educação e reuniões e aprendizado remoto.

### 3.1.5. Conceitos necessários para desenvolver em RV e RA

Tanto a Realidade Virtual quanto a Aumentada necessitam de dois componentes importantes para funcionar: O Hardware, que compreende a parte física do projeto e envolve dispositivos de entrada e saída, além de ser o meio que permitirá a manipulação do usuário com o ambiente, e o software, que possui o código, modelos, e outros dispositivos que se comunicarão e irão reagir com o usuário, além de prover imagens e outras funções sensoriais.

#### 3.1.5.1. Hardware

O hardware de realidade aumentada pode usar equipamentos de realidade virtual, mas muitas vezes não obstrui as mãos, que devem atuar naturalmente em um ambiente misto. Neste caso, o uso de visão computacional e tecnologia de rastreamento visual de processamento de imagem é muito importante. 

Normalmente, o dispositivo utilizado para a execução da Realidade Aumentada é um celular, tablet ou similar. A potência de processamento principal e das placas de apoio, para tratar as necessidades de multimídia deve ser alta o suficiente para garantir a execução, em tempo real, das seguintes ações: tratamento de vídeo; processamento gráfico 3D; geração de imagens misturadas; incorporação de som; rastreamento de posição do usuário em relação ao seu ambiente, câmera para a projeção de objetos; etc. (Kirner, 2006).

![Hardware](https://user-images.githubusercontent.com/64936673/121264707-f9185f00-c88d-11eb-87cd-9e4629b31d8f.png)
<p align="center">
    Figura 2 - Hardware do tipo HMD para RV
</p>

#### 3.1.5.2. Software

Kirner (2006) também nos diz que o software de realidade aumentada é usado para implementar objetos virtuais e integrá-los ao ambiente real, incluindo alguns comportamentos. Ele pode usar elementos auxiliares para a captura de posições ou os próprios elementos do cenário real.

Muitos dos programas requerem bibliotecas e códigos, em geral tais bibliotecas requerem interface para dispositivos de interação, operação e gerenciamento de monitores/projetores, multiprocessamento, cálculo da perspectiva de acordo com o ponto de visão do usuário, configurações para diferentes sistemas dentre outros.

![Software](https://user-images.githubusercontent.com/64936673/121265400-1f8aca00-c88f-11eb-8c55-ce048fdc56f1.png)

<p align="center">
    Figura 3 - Software Unity para VR e AR
</p>

