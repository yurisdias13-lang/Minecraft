# Minecraft 26.3 — Base com forja automática

[Baixar o mundo completo — forja e farms (ZIP)](https://github.com/yurisdias13-lang/Minecraft/raw/refs/heads/main/mapas/Mapa_Minecraft_26.3_Base_Completa_Forja_e_Farms.zip)

Mundo de sobrevivência com casa de dois andares, cozinha, quarto, varanda, armazenamento, caminhos iluminados e quatro farms de comida. Há **100 frangos assados e 100 lingotes de ferro** nos baús sinalizados dentro da casa. A nova casa de combustível contém 45 caldeirões que circulam por pistões sob as estalactites, com uma cabine iluminada para coletar lava. O ejetor da farm de galinha começa com **144 ovos: nove pilhas de 16**.

- **Galinhas:** câmara 1×1 sobre a laje e diretamente sob a lava. O datapack incluído mantém os pintinhos dessa farm imóveis e protegidos do fogo até crescer; nas adultas, o comportamento normal volta e a proteção sai. Os itens reais são mantidos junto dos funis para não queimarem antes de chegar ao baú.
- **Cenoura e batata:** fazendeiros colhem, replantam e compartilham os excedentes; coletores encaminham os itens aos baús.
- **Trigo:** fazendeiro colhe e replanta; coletores sob a plantação levam o trigo ao baú da escada.
- **Ferro:** farm automática com cinco aldeões protegidos e camas, sem zumbi.

## Esculturas menores

O **golem tem 17 blocos de altura**, contando a cobertura, em vez dos 55 da versão anterior. A largura caiu de 53 para 15 blocos. Peito, ombros, braços, costas, orelhas e pés receberam volumes que avançam um ou dois blocos, dando profundidade à silhueta. A parte funcional da farm de ferro foi transferida para uma sala fechada no subsolo, mantendo os mesmos cinco aldeões, camas, água e área de nascimento dos golems. Um ejetor com observadores e uma coluna de bolhas levam a produção real para o **baú da superfície em X −727, Y 64, Z −311**. A janela fica entre os pés do golem; use o baú pelo lado da casa, olhando para sul. O quadro de ferro identifica a coleta. Uma escada de manutenção fica sob o alçapão em **X −715, Y 64, Z −306**.

A **galinha tem 14 blocos de altura e 14 de largura**, incluindo a laje e as asas; antes tinha 22 de altura e 21 de largura. A cobertura foi ajustada ao tamanho da incubadora, sem alterar a câmara dos pintinhos, as reprodutoras ou o circuito dos ovos. O baú de frango assado continua no balcão da frente, em **X −781, Y 63, Z −315**, com um baú de reserva em **X −786, Y 63, Z −315**. Corpo, cabeça, bico, olhos, papo, pés e balcão compartilham o mesmo eixo; os quadros também foram alinhados.

Os estoques foram preservados. As duas esculturas receberam bases baixas, papoulas, arbustos, lanternas e caminhos; o ninho de feno da galinha ficou menor. O caminho para a casa de lava continua aberto.

## Usando o salão quadrado

Coloque os itens no **baú duplo de entrada dentro da casa**, em **X −769, Y 64, Z −301**, identificado pelo quadro com um baú. O sistema distribui os itens automaticamente enquanto a base estiver carregada.

- **Salão central de 31 × 31 blocos**, com o centro aberto, piso ornamental e lanternas suspensas. Do centro (**X −764, Y 49, Z −307**), os 200 quadros ficam visíveis nas quatro paredes.
- **200 tipos de itens**, cada um com seu baú duplo. Os armários têm duas fileiras alcançáveis do mesmo piso, sem precisar subir para abrir os baús superiores.
- **Quadros luminosos com os próprios itens** identificam os destinos. Os mecanismos ficam atrás dos armários, com transporte por correnteza e gelo azul.
- **Escada de pedra dentro da casa**, com entrada em **X −775, Y 64, Z −309**. O caminho recebeu revestimento de pedra e madeira, teto acabado, iluminação e paredes que fecham a visão dos circuitos. As transições dos degraus tiveram o teto levantado, e o piso do túnel sob a correnteza desceu um bloco: é possível passar em pé, nas duas faixas da escada. Ela chega por um acesso lateral, deixando o centro do salão livre. O baú inicial de ferramentas foi preservado e reposicionado para **X −772, Y 64, Z −310**.
- **Três baús duplos de sobras**, na parede norte, em **X −765, Y 49–51, Z −322**, identificados pelo quadro de uma trouxa. Recebem itens sem filtro, equipamentos, itens com componentes diferentes e excessos quando um destino estiver cheio.

A separação é gradual. A lista de itens e as coordenadas de cada destino estão em `ITENS-SEPARADOS.txt` no ZIP. Os baús das farms continuam independentes: coloque a produção na entrada quando quiser organizá-la.

## Forja automática, abaixo do depósito

Uma **escada normal de pedra, com dois blocos de largura**, desce pelo canto sudeste do salão. A entrada fica em **X −756, Y 49, Z −295**, perto do quadro de forno no piso. O andar inferior tem oficina decorada, iluminação, bancada, bigorna e **oito fornos comuns**, que aceitam todas as receitas normais de forno.

Há três estações com quadros dos itens:

| Estação | Quadro | X | Y | Z |
| --- | --- | ---: | ---: | ---: |
| Materiais para queimar | Ferro bruto | -778 | 39 | -314 |
| Combustível | Carvão | -759 | 39 | -316 |
| Produtos prontos (baú duplo) | Lingote | -762 | 37 | -304 |

1. Abasteça o baú de combustível. Ele aceita combustíveis normais do Minecraft, incluindo **baldes de lava** da farm.
2. Coloque os materiais no outro baú. Um carrinho com funil distribui os materiais por cima dos fornos; um **carrinho com baú**, separado e com espaço para mais baldes, distribui o combustível pelas laterais.
3. Retire a produção no baú duplo de saída. **Os baldes vazios também voltam para esse baú.**

Os carrinhos fazem uma pausa para carregar e partem automaticamente. A descarga e a coleta são feitas por funis escondidos na estrutura. O sistema funciona enquanto a região estiver carregada. Os três baús são acessíveis a pé, as tampas têm espaço para abrir e os circuitos ficam atrás do acabamento. A máquina é entregue vazia, sem os itens usados na validação.

## Hortas reformadas

As estufas de **cenoura, batata e trigo** receberam telhados inclinados de vidro e madeira, varandas, quadros com os cultivos, abrigos para a coleta, canteiros de flores e caminhos iluminados. Os materiais combinam com a casa e com o salão.

A colheita automática pelos aldeões foi preservada, assim como os canteiros, camas, composteiras, sinos, trilhos, funis e baús de produção. As coordenadas de coleta continuam as mesmas.

## Usando a farm de lava

A casa recebeu **pedra negra, basalto, vidro laranja, desenhos de chamas e dois braseiros protegidos por vidro**. Siga a ponte a oeste da base. O **botão vermelho sobre o bloco amarelo**, em **X −799, Y 64, Z −319**, abre a porta de ferro. Há outro botão do lado de dentro, além de uma placa de pressão para sair. Depois de entrar, siga até a cabine de coleta.

1. Pegue os 16 baldes vazios no baú da cabine e deixe espaço no inventário.
2. Desligue a alavanca **PAUSAR A FARM**: os caldeirões começam a circular. Alavanca ligada pausa a farm; espere alguns segundos até os pistões terminarem a sequência.
3. Fique no tapete amarelo e use o balde no caldeirão cheio que passar pela janela. Guarde os baldes cheios no baú duplo.

O enchimento por estalactites e o transporte são automáticos. A coleta com o balde é feita pelo jogador. Os 45 caldeirões começam cheios para a primeira coleta; depois voltam a encher gradualmente enquanto a região estiver carregada. A farm é entregue pausada, com porta de ferro, iluminação, cobertura e cabine separada do mecanismo. Não quebre as fontes de lava ou o circuito sob o piso.

## Instalação

A correção da farm já está incluída e ativada no mundo completo. Basta copiar o save e abrir o jogo.

1. Baixe e extraia o ZIP.
2. Copie a pasta `Base_Completa_26_3_Forja_e_Farms`, que contém `level.dat`, para a pasta `saves` usada pelo seu perfil Minecraft Java 26.3.
3. Abra seu perfil Forge 26.3 e selecione **Base Completa - Forja e Farms** em **Um jogador**.

Esta versão é uma cópia separada: não atualiza automaticamente um save no qual você já jogou. **Preserve o mundo anterior para manter seu progresso.**

Se não encontrar a pasta correta de saves, selecione um mundo no Minecraft, escolha **Editar → Abrir pasta do mundo** e volte uma pasta. Feche o jogo antes de copiar os arquivos.

O mundo usa blocos, entidades e datapack vanilla e foi testado no servidor oficial Minecraft Java 26.3. O carregamento com Forge e os mods do seu perfil não foi testado neste ambiente. Não requer mods adicionais.

## Onde encontrar

| Local | X | Y | Z |
| --- | ---: | ---: | ---: |
| Entrada de itens, dentro da casa | -769 | 64 | -301 |
| Entrada da escada de pedra | -775 | 64 | -309 |
| Centro do salão | -764 | 49 | -307 |
| Baús de sobras (parede norte) | -765 | 49–51 | -322 |
| Entrada da casa de lava | -800 | 64 | -318 |
| Botão externo da casa de lava | -799 | 64 | -319 |
| Escada para a forja (dentro do depósito) | -756 | 49 | -295 |
| Tapete para coletar lava | -810 | 64 | -312 |
| Alavanca de pausa | -818 | 64 | -319 |
| Baú de baldes vazios | -812 | 64 | -308 |
| Início | -768 | 64 | -316 |
| Porta da casa | -768 | 64 | -312 |
| Reserva de 100 frangos assados | -764 | 64 | -297 |
| Reserva de 100 lingotes | -762 | 64 | -297 |
| Coleta de frango assado (frente da galinha) | -781 | 63 | -315 |
| Coleta de ferro (entre os pés do golem) | -727 | 64 | -311 |
| Alçapão de manutenção da farm de ferro | -715 | 64 | -306 |
| Coleta de cenouras | -786 | 63 | -351 |
| Coleta de batatas | -768 | 63 | -351 |
| Coleta de trigo (desça a escada) | -760 | 61 | -350 |

Fique perto da base para manter as farms carregadas. Preserve aldeões, composteiras, sinos, camas e coletores. Os pintinhos levam cerca de 20 minutos para crescer, e os aldeões trabalham durante o dia. As reservas da casa ficam separadas dos baús que recebem a produção contínua.

## Validação

Na reforma atual, a conferência de colisões percorreu **1.732 posições nas duas faixas das escadas**, com uma altura de 2,1 blocos, sem pontos que exigissem agachar. A inspeção de visão do acesso ao depósito passou por 135 posições sem encontrar terra ou circuitos expostos. Os seis baús de coleta e de serviço tiveram a linha de uso e o espaço da tampa conferidos.

A forja recebeu **64 ferros brutos e 64 areias**, entregou os 64 lingotes e 64 vidros, e os oito fornos receberam materiais e combustível pelos carrinhos. Outro teste distribuiu baldes de lava, transformou 64 pedregulhos em 64 pedras e devolveu oito baldes vazios. Após salvar e reabrir o mundo, novos materiais e combustível produziram mais oito lingotes automaticamente. Os itens, combustíveis e registros de experiência dos testes foram retirados.

Os botões externo e interno da casa de lava abriram e fecharam a porta. A esteira decorada movimentou um caldeirão marcado, concluiu a sequência ao pausar e terminou com todos os pistões recolhidos. Os 45 caldeirões foram entregues cheios de lava novamente.

Os **200 destinos do depósito** foram testados de novo, usando as duas metades da entrada, e um equipamento nomeado chegou às sobras com o nome preservado. As reservas dos filtros permaneceram corretas. Em um dia do jogo, os estoques das farms subiram de 757 para 797 lingotes, de 169 para 195 frangos assados, de 1.112 para 1.152 cenouras, de 1.114 para 1.194 batatas e de 386 para 404 trigos; todos os aldeões permaneceram saudáveis.


Sobrevivência, dificuldade normal, comandos desativados. Seed: `2751751648501333327`. Instruções completas no `LEIA-ME.txt` dentro do ZIP.

## Versões anteriores

- [Esculturas compactas, antes da forja e dos ajustes de acesso](mapas/Mapa_Minecraft_26.3_Base_Completa_Farms_Compactas.zip)

- [Esculturas grandes, antes da redução](mapas/Mapa_Minecraft_26.3_Base_Completa_Farms_Decoradas.zip)

- [Salão quadrado e hortas, antes das esculturas](mapas/Mapa_Minecraft_26.3_Base_Completa_Salao_e_Hortas.zip)

- [Depósito anterior em galerias, com quadros](mapas/Mapa_Minecraft_26.3_Base_Completa_Deposito_Visual.zip)

- [Depósito anterior, em dois andares e com placas](mapas/Mapa_Minecraft_26.3_Base_Completa_Deposito.zip)

- [Base Completa com Lava, sem o depósito](mapas/Mapa_Minecraft_26.3_Base_Completa_Lava.zip)

- [Base Completa Corrigida, sem a farm de lava](mapas/Mapa_Minecraft_26.3_Base_Completa_Corrigida.zip)

- [Base Completa anterior à correção da farm](mapas/Mapa_Minecraft_26.3_Base_Completa.zip)

- [Começo com Farms — frango assado](mapas/Mapa_Minecraft_26.3_Frango_Assado.zip)
- [Começo com Farms — abate manual](mapas/Mapa_Minecraft_26.3.zip)

## Correção da farm de galinhas no save atual

[Baixar o corretor (datapack, 4 KB)](https://github.com/yurisdias13-lang/Minecraft/raw/refs/heads/main/correcoes/Correcao_Galinhas_26.3_Protegida.zip)

O corretor fecha a área lateral e mantém as aves numa câmara 1×1 sob a lava. Os pintinhos dessa farm ficam imóveis e resistentes ao fogo até crescer; as adultas recuperam o comportamento normal, perdem a proteção e são cozidas. Os itens reais produzidos são mantidos junto dos funis para não queimarem antes da coleta. Não cria comida por comandos.

1. Faça uma cópia de segurança do seu mundo e feche o jogo.
2. Copie o ZIP **sem extrair** para a pasta `datapacks` dentro do seu mundo atual.
3. Abra esse mundo e fique perto da farm original (`X=-782 Y=65 Z=-320`). Ative comandos em **ESC → Abrir para LAN → Permitir comandos**.
4. Execute `/reload` e depois `/function base_galinhas:aplicar`.

As aves que estavam na câmara vão para o galinheiro ao lado. As reprodutoras, a casa, as hortas e o inventário do jogador são preservados. O corretor continua funcionando depois de sair e reabrir o mundo; não exige mods adicionais.

Antes de remover o datapack, fique perto da farm e execute `/function base_galinhas:desativar`, para restaurar o comportamento das aves gerenciadas. Depois feche o jogo e remova o ZIP. As instruções completas estão no `LEIA-ME.txt` do arquivo.

Validação no servidor oficial 26.3: 8 pintinhos acompanhados até crescer, nenhuma perda prematura, todas as 8 adultas cozidas e 8 frangos assados recolhidos. Não testado com Forge ou com os mods do perfil do jogador.
