<h1>Flexbox </h1>
<p>Flexbox (ou Flexible Box Layout) é um modelo de layout CSS que permite criar layouts mais flexíveis e responsivos. 
  Ele facilita o alinhamento e a distribuição de espaço entre os itens de um contêiner, mesmo quando suas dimensões são desconhecidas ou dinâmicas.
Ao usar o Flexbox, você pode controlar a direção, o alinhamento, o espaçamento e o tamanho dos itens dentro de um contêiner de maneira eficiente, 
sem a necessidade de posicionamento absoluto ou outras abordagens complexas.</p>

<h2>Como funciona o Flexbox?</h2>
<p>
  O Flexbox é baseado em dois componentes principais:
</p>
<ul>
  <li>Contêiner Flexível: O elemento pai, onde o Flexbox é aplicado. Este contêiner gerencia o comportamento dos itens dentro dele.</li>
  <li>Itens Flexíveis: Os elementos filhos do contêiner flexível, que são os itens que podem ser manipulados pelo Flexbox.
</li>
</ul>

<h2>Propriedades do Contêiner Flexível</h2>
<p>Essas propriedades são aplicadas ao contêiner para controlar o layout dos itens dentro dele.</p>

<h2>display: flex</h2>
<p>Define o contêiner como um contêiner flexível, ativando o comportamento Flexbox.</p>

<pre>
  <code>
    Exemplo:
   css
  .container {
    display: flex;
  }
  </code>
</pre>

<table border="1" cellpadding="10">
  <thead>
    <tr>
      <th>Propriedade</th>
      <th>Descrição</th>
      <th>Valores</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>flex-direction</td>
      <td>Controla a direção principal dos itens dentro do contêiner (eixo horizontal ou vertical).</td>
      <td>
        <ul>
          <li><strong>row</strong> (padrão): os itens são dispostos horizontalmente.</li>
          <li><strong>column</strong>: os itens são dispostos verticalmente.</li>
          <li><strong>row-reverse</strong>: os itens são dispostos na ordem inversa horizontalmente.</li>
          <li><strong>column-reverse</strong>: os itens são dispostos na ordem inversa verticalmente.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<table border="1" cellpadding="10">
  <thead>
    <tr>
      <th>Propriedade</th>
      <th>Descrição</th>
      <th>Valores</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>justify-content</td>
      <td>Controla o alinhamento dos itens ao longo do eixo principal (horizontal ou vertical).</td>
      <td>
        <ul>
          <li><strong>flex-start</strong>: alinha os itens no início do contêiner.</li>
          <li><strong>flex-end</strong>: alinha os itens no final do contêiner.</li>
          <li><strong>center</strong>: centraliza os itens.</li>
          <li><strong>space-between</strong>: distribui o espaço uniformemente entre os itens.</li>
          <li><strong>space-around</strong>: distribui o espaço uniformemente ao redor dos itens.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
<table border="1" cellpadding="10">
  <thead>
    <tr>
      <th>Propriedade</th>
      <th>Descrição</th>
      <th>Valores</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>align-items</td>
      <td>Controla o alinhamento dos itens ao longo do eixo transversal (perpendicular ao eixo principal).</td>
      <td>
        <ul>
          <li><strong>flex-start</strong>: alinha os itens no topo (se a direção for `row`).</li>
          <li><strong>flex-end</strong>: alinha os itens na parte inferior (se a direção for `row`).</li>
          <li><strong>center</strong>: centraliza os itens no eixo transversal.</li>
          <li><strong>baseline</strong>: alinha os itens ao longo da linha de base do texto.</li>
          <li><strong>stretch</strong>: estica os itens para preencher o contêiner.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
<table border="1" cellpadding="10">
  <thead>
    <tr>
      <th>Propriedade</th>
      <th>Descrição</th>
      <th>Valores</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>flex-wrap</td>
      <td>Define se os itens devem se mover para a próxima linha/coluna quando o espaço for insuficiente.</td>
      <td>
        <ul>
          <li><strong>nowrap</strong> (padrão): todos os itens ficam em uma única linha/coluna.</li>
          <li><strong>wrap</strong>: os itens quebram e se movem para a próxima linha/coluna.</li>
          <li><strong>wrap-reverse</strong>: os itens quebram e se movem para a próxima linha/coluna, mas na direção oposta.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
