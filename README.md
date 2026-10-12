# Maquete de Palete 3D

Programa para desenhar uma palete em 3D com as medidas de cada peça e gerar a ficha técnica em PDF.

Funciona no navegador (Chrome, Edge ou Firefox) e não precisa de instalação nem de internet.

## Como usar

1. Descarrega o programa:
   - No GitHub, carrega no botão verde **Code** e depois em **Download ZIP**.
   - Extrai o ZIP para uma pasta do teu PC (por exemplo, `Documentos\maquete-palete`).
2. Abre o ficheiro **`index.html`** com duplo clique. Abre no navegador.
3. Preenche as medidas:
   - **Ripas**: comprimento, largura e espessura. As ripas do topo e da base são iguais. A base leva sempre 3 ripas.
   - **Nº de ripas no topo** e **folga entre ripas**: definem a largura da palete e o comprimento das travessas.
   - **Travessas (3)**: largura e espessura. O comprimento é calculado sozinho.
   - **Tacos (9 iguais)**: comprimento, largura e altura.
4. Na secção **Ficha técnica**, escreve a designação e a descrição e revê os restantes campos.
5. Carrega em **Descarregar ficha técnica (PDF)**. O ficheiro vai para a pasta de transferências.

As medidas e os campos da ficha ficam guardados no navegador desse PC. Na próxima vez que abrires o programa, voltam a aparecer.

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
