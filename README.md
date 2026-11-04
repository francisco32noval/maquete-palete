# Maquete de Palete 3D

Programa para desenhar uma palete em 3D com as medidas de cada peça e gerar a ficha técnica em PDF.

Funciona no navegador (Chrome, Edge ou Firefox) e não precisa de instalação nem de internet.

## Como usar

1. Descarrega o programa:
   - No GitHub, carrega no botão verde **Code** e depois em **Download ZIP**.
   - Extrai o ZIP para uma pasta do teu PC (por exemplo, `Documentos\maquete-palete`).
2. Abre o ficheiro **`index.html`** com duplo clique. Abre no navegador.
3. Na primeira vez, escolhe a unidade em que vais escrever as medidas: **mm**, **cm** ou **m**. Podes mudá-la depois no topo do painel. As medidas já escritas são convertidas e a ficha técnica sai na mesma unidade.
4. Preenche as medidas:
   - **Ripas**: comprimento, largura e espessura. As ripas do topo e da base são iguais. A base leva sempre 3 ripas.
   - **Nº de ripas no topo**: ficam distribuídas por igual ao longo das travessas. A folga entre ripas é calculada sozinha.
   - **Travessas (3)**: comprimento, largura e espessura. O comprimento da travessa é a largura da palete.
   - **Tacos (9 iguais)**: comprimento, largura e altura.
5. Na secção **Ficha técnica**, carrega em **Editar**. Na janela que abre, escreve a designação e a descrição e revê os restantes campos.
6. Em **Empresa no topo da ficha**, escolhe a empresa que aparece no topo de cada página (AcustiKideia ou Habitualescolha) ou **Sem empresa**. A escolha fica gravada com a palete.
7. Carrega em **Descarregar ficha técnica (PDF)**. O ficheiro vai para a pasta de transferências.

As medidas e os campos da ficha ficam guardados no navegador desse PC. Na próxima vez que abrires o programa, voltam a aparecer.

## Paletes guardadas

Para não teres de escrever as mesmas medidas várias vezes:

- **Gravar**: escreve um nome na secção **Paletes guardadas** e carrega em **Gravar**. Fica gravado tudo: as medidas, a unidade e os campos da ficha técnica. Se o nome já existir, o botão passa a **Substituir**.
- **Abrir**: carrega em **Abrir** ao lado da palete. As medidas e a ficha voltam a aparecer.
- **Apagar**: carrega em **Apagar** e depois em **Confirmar**.
- **Exportar / Importar**: as paletes ficam gravadas só no navegador deste PC. Usa **Exportar** para criar um ficheiro `paletes-guardadas.json`, que serve de cópia de segurança e pode ser enviado a colegas. Do outro lado, basta carregar em **Importar** e escolher esse ficheiro.

## Atalhos na maquete

- Arrastar com o rato: rodar a palete.
- Roda do rato: aproximar e afastar.
- Clicar numa peça: ver as medidas dessa peça.
- Botão **Esconder medidas**: mostra só a palete, sem caixas.
- **Separar camadas**: afasta as ripas, os tacos e as travessas para se verem melhor.

## Atualizar para a versão mais recente

Volta a descarregar o ZIP e substitui a pasta antiga. As medidas guardadas mantêm-se se a pasta ficar no mesmo sítio.

## Conteúdo

- `index.html` — o programa.
- `lib/` — bibliotecas usadas pelo programa: three.js para o 3D e jsPDF para gerar o PDF. As licenças estão na mesma pasta.
