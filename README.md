# Caça Selvagem — mod de caça para Minecraft 1.20.1 (Forge 47.2.0)

Conteúdo: Rifle de Caça (luneta, ferrolho), Espingarda Pump, munições, e 3 armadilhas
(Urso, Laço, Rede) com modelos 3D feitos de dezenas de cubos. Receitas em português/inglês.

## Como gerar o .jar (escolha UMA opção)

### A) Sem instalar nada (GitHub Actions)
1. Crie um repositório no GitHub e envie TODO o conteúdo desta pasta.
2. Aba **Actions** > "Compilar mod" > aguarde (~5 min).
3. Baixe o artefato **cacaselvagem-jar**: o .jar está dentro.

### B) No seu PC (Java 17 + Gradle 8.1.1)
    gradle build
O arquivo sai em `build/libs/cacaselvagem-1.0.0.jar` (copie para a pasta `mods` do Forge 1.20.1).

## Ajustes
- `tools/gen_assets.py` regenera texturas, modelos, receitas e traduções (`python3 tools/gen_assets.py .`).
- Posição da arma na mão: edite `GUN_DISPLAY` nesse script (ou abra o JSON no Blockbench).
- Armadilhas: agache + botão direito desarma; botão direito rearma. Afetam jogadores também.
