<p align="center">
  <img src="https://github.com/hildocosta/hildocosta-Curso-Java--Nelio-Alves/blob/main/logo.png" width="300">
</p>
<h1 align="center">📂 Explorando Caminho do Arquivo em Java</h1>
<p>🔥 Bem-vindo ao repositório dedicado à exploração do conceito de caminho do arquivo na linguagem de programação Java. Aqui, você encontrará informações e exemplos práticos sobre como lidar com caminhos de arquivos em seus programas Java.</p>
<p>🎓 Este repositório é voltado para estudantes e desenvolvedores que desejam aprender como trabalhar com caminhos de arquivos de forma eficiente e prática em Java. Aqui, você encontrará explicações detalhadas, exemplos de código e exercícios para aprimorar suas habilidades na manipulação de caminhos de arquivos.</p>
<p>💡 Ao explorar o conceito de caminho do arquivo em Java, você aprenderá como representar e manipular caminhos de arquivos usando strings e a classe File. Essas ferramentas permitem que você trabalhe com caminhos de forma fácil e eficaz, garantindo o acesso aos arquivos necessários em seus programas Java.</p>
<h2 align="center">🔒 Licença</h2>
<p>⚖️ Este projeto está licenciado sob a <a href="LICENSE">Licença MIT</a>.</p>
<h2 align="center">📧 Contato</h2>
<h3>🔗 Redes Sociais e Contato</h3>
<ul>
  <li>📌 GitHub: <a href="https://github.com/example">example</a></li>
  <li>💼 LinkedIn: <a href="https://www.linkedin.com/in/example/">Example Name</a></li>
  <li>✉️ Email: example@example.com</li>
</ul>
<p>Agora que estamos preparados, vamos explorar como lidar com caminhos de arquivos em Java!</p>
<h2 align="center">🚀 Vamos Começar</h2>
<h3>🔥 Caminho do Arquivo em Java</h3>
<p>O caminho do arquivo em Java é a localização física de um arquivo no sistema de arquivos do computador. Ele pode ser representado por uma string contendo o caminho completo do arquivo ou por um objeto da classe File.</p>
<p>Veja um exemplo de código para obter informações sobre o caminho de um arquivo em Java:</p>

import java.io.File;

public class Main {

    public static void main(String[] args) {
        
        // Caminho do arquivo
        String caminhoArquivo = "caminho/do/arquivo.txt";
        
        // Instancia um objeto File com o caminho do arquivo
        File arquivo = new File(caminhoArquivo);
        
        // Exibe informações sobre o caminho do arquivo
        System.out.println("Caminho do arquivo: " + arquivo.getPath());
        System.out.println("Nome do arquivo: " + arquivo.getName());
        System.out.println("Diretório pai: " + arquivo.getParent());
    }
}

<p>Este código cria um objeto File com o caminho do arquivo especificado e exibe informações sobre o caminho, o nome do arquivo e o diretório pai.</p>
<p>Agora que você entende como lidar com caminhos de arquivos em Java, experimente manipular diferentes caminhos de arquivos para praticar e aprimorar suas habilidades!</p>

<h2> Exercício 01 </h2>
<p>💥 Fazer um programa para ler  o caminho de um arquivo .csv contendo os dados de itens vendidos. Cada item possui um nome, preço unitário e quantidade, separados por vírgula.<\p>
<p> Você deve gerar um novo arquivo chamado "summary.csv", localizado em uma subpasta chamada "out" a partir da pasta original do arquivo de origem, contendo apenas o nome e o valor total para aquele item (preço unitário multiplicado pela quantidade), conforme exemplo.</p>

<h3>Exemplo:</h3>
<p align="center">
  <img src="https://github.com/hildocosta/Caminho-do-Arquivo-/blob/main/imagem_01.png">
</p>

