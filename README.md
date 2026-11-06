# Minecraft 26.3 — Base Completa com Depósito Automático

[Baixar o mundo completo com depósito automático (ZIP)](https://github.com/yurisdias13-lang/Minecraft/raw/refs/heads/main/mapas/Mapa_Minecraft_26.3_Base_Completa_Deposito.zip)

Mundo de sobrevivência com casa de dois andares, cozinha, quarto, varanda, armazenamento, caminhos iluminados e quatro farms de comida. Há **100 frangos assados e 100 lingotes de ferro** nos baús sinalizados dentro da casa. A nova casa de combustível contém 45 caldeirões que circulam por pistões sob as estalactites, com uma cabine iluminada para coletar lava. O ejetor da farm de galinha começa com **144 ovos: nove pilhas de 16**.

- **Galinhas:** câmara 1×1 sobre a laje e diretamente sob a lava. O datapack incluído mantém os pintinhos dessa farm imóveis e protegidos do fogo até crescer; nas adultas, o comportamento normal volta e a proteção sai. Os itens reais são mantidos junto dos funis para não queimarem antes de chegar ao baú.
- **Cenoura e batata:** fazendeiros colhem, replantam e compartilham os excedentes; coletores encaminham os itens aos baús.
- **Trigo:** fazendeiro colhe e replanta; coletores sob a plantação levam o trigo ao baú da escada.
- **Ferro:** farm automática com cinco aldeões protegidos e camas, sem zumbi.

## Usando o depósito automático

Coloque os itens no **baú duplo de entrada dentro da casa**, em **X −769, Y 64, Z −301**. O sistema usa funis e redstone para distribuir os itens sozinho. A organização acontece gradualmente; os últimos filtros e as sobras podem levar alguns minutos para receber os itens. Fique perto da casa para manter o depósito carregado.

- **200 tipos de itens comuns**, com um baú duplo identificado para cada tipo, distribuídos em dois andares subterrâneos.
- Primeiro andar: pedras, terra, materiais do Nether, madeiras, minérios e lingotes.
- Segundo andar: comida, plantas, carnes, drops, exploração, vidro e os 16 corantes.
- **Três baús duplos de sobras** no segundo andar recebem itens sem filtro, ferramentas, armaduras, itens com componentes diferentes e excessos quando o armazenamento do tipo estiver cheio.

Abra o alçapão em **X −769, Y 63, Z −303** e desça pela escada. Os baús de sobras ficam em **X −743, Y 37–39, Z −298**. A lista completa de itens e as coordenadas de cada baú estão em `ITENS-SEPARADOS.txt` no ZIP. Use os baús identificados; preserve os funis, as reservas dos filtros e os papéis nomeados atrás do vidro. O depósito organiza os itens colocados na entrada, sem esvaziar automaticamente os baús das farms.

## Usando a farm de lava

Siga a ponte a oeste da base até a casa de combustível. Entre pela porta de ferro usando o botão e vá à cabine de coleta.

1. Pegue os 16 baldes vazios no baú da cabine e deixe espaço no inventário.
2. Desligue a alavanca **PAUSAR A FARM**: os caldeirões começam a circular. Alavanca ligada pausa a farm; espere alguns segundos até os pistões terminarem a sequência.
3. Fique no tapete amarelo e use o balde no caldeirão cheio que passar pela janela. Guarde os baldes cheios no baú duplo.

O enchimento por estalactites e o transporte são automáticos. A coleta com o balde é feita pelo jogador. Os 45 caldeirões começam cheios para a primeira coleta; depois voltam a encher gradualmente enquanto a região estiver carregada. A farm é entregue pausada, com porta de ferro, iluminação, cobertura e cabine separada do mecanismo. Não quebre as fontes de lava ou o circuito sob o piso.

## Instalação

A correção da farm já está incluída e ativada no mundo completo. Basta copiar o save e abrir o jogo.

1. Baixe e extraia o ZIP.
2. Copie a pasta `Base_Completa_26_3_Deposito`, que contém `level.dat`, para a pasta `saves` usada pelo seu perfil Minecraft Java 26.3.
3. Abra seu perfil Forge 26.3 e selecione **Base Completa - Deposito Automatico** em **Um jogador**.

Esta versão é uma cópia separada: não atualiza automaticamente um save no qual você já jogou. **Preserve o mundo anterior para manter seu progresso.**

Se não encontrar a pasta correta de saves, selecione um mundo no Minecraft, escolha **Editar → Abrir pasta do mundo** e volte uma pasta. Feche o jogo antes de copiar os arquivos.

O mundo usa blocos, entidades e datapack vanilla e foi testado no servidor oficial Minecraft Java 26.3. O carregamento com Forge e os mods do seu perfil não foi testado neste ambiente. Não requer mods adicionais.

## Onde encontrar

| Local | X | Y | Z |
| --- | ---: | ---: | ---: |
| Entrada de itens, dentro da casa | -769 | 64 | -301 |
| Alçapão do depósito | -769 | 63 | -303 |
| Baús de sobras (segundo andar) | -743 | 37–39 | -298 |
| Entrada da casa de lava | -800 | 64 | -318 |
| Tapete para coletar lava | -810 | 64 | -312 |
| Alavanca de pausa | -818 | 64 | -319 |
| Baú de baldes vazios | -812 | 64 | -308 |
| Início | -768 | 64 | -316 |
| Porta da casa | -768 | 64 | -312 |
| Reserva de 100 frangos assados | -764 | 64 | -297 |
| Reserva de 100 lingotes | -762 | 64 | -297 |
| Coleta de frango assado | -780 | 63 | -320 |
| Coleta de ferro | -736 | 64 | -317 |
| Coleta de cenouras | -786 | 63 | -351 |
| Coleta de batatas | -768 | 63 | -351 |
| Coleta de trigo (desça a escada) | -760 | 61 | -350 |

Fique perto da base para manter as farms carregadas. Preserve aldeões, composteiras, sinos, camas e coletores. Os pintinhos levam cerca de 20 minutos para crescer, e os aldeões trabalham durante o dia. As reservas da casa ficam separadas dos baús que recebem a produção contínua.

## Validação

O depósito foi testado com uma amostra de cada um dos 200 tipos, depositadas pelas duas metades do baú de entrada: todas chegaram ao destino e as reservas dos filtros foram preservadas. Itens sem filtro, itens nomeados e uma picareta encantada foram encaminhados às sobras. Com um destino e seu buffer lotados, 64 unidades excedentes foram para as sobras enquanto 64 unidades do item vizinho foram separadas normalmente; os outros 199 filtros mantiveram suas reservas. A iluminação dos dois andares e o espaço acima de todos os baús foram conferidos. Após salvar e reabrir, o primeiro filtro, o último e as sobras funcionaram novamente. Os itens usados nos testes foram retirados antes da entrega.

A esteira foi testada em quatro voltas manuais, com conferência de cada empurrão, e em nove testes automáticos de partida e pausa. Um caldeirão marcado chegou à janela de coleta. Em 30.000 ticks naturais, 30 caldeirões encheram; os caldeirões cheios mantiveram a lava durante o transporte. A casa foi conferida após atualizar a iluminação: nenhuma das 348 posições de piso livre ficou sem luz. O mundo foi salvo e reaberto, e o circuito voltou a circular sem precisar de um novo pulso manual. Uma carga de 144 ovos foi consumida durante o teste e produziu frango assado; os nove slots foram reabastecidos antes da entrega.

Quatro dias do jogo confirmaram crescimento, colheita, replantio e produção de frango assado, cenoura, batata e trigo nos respectivos baús. Os pintinhos acompanhados ficaram saudáveis. Após ajustar a altura das camas e as passagens, dois dias adicionais não registraram solo pisoteado. Todos os fazendeiros e os cinco aldeões da farm de ferro permaneceram com vida completa. Os estoques da casa foram conferidos: 100 frangos assados e 100 lingotes.

A versão completa corrigida também foi salva e reaberta: o datapack continuou ativo e entregou frango assado no baú. As reservas de 100 frangos e 100 lingotes foram conferidas novamente.

Sobrevivência, dificuldade normal, comandos desativados. Seed: `2751751648501333327`. Instruções completas no `LEIA-ME.txt` dentro do ZIP.

## Versões anteriores

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
