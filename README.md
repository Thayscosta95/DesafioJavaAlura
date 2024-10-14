<h1>Desafio Java - Curso Alura</h1>

<br>

<h2>Projeto: Músicas Preferidas</h2>

<br>

<h2>Objetivos do projeto</h2>
<p>Foi feito a implementação uma aplicação para cadastrar nossas músicas e podcasts preferidos, modelando as classes utilizando os conceitos de orientação a objetos: abstração, herança, encapsulamento e polimorfismo.</p>

<br>
<li> Criação uma classe Audio com os atributos (titulo, totalReproducoes, totalCurtidas e classificacao). </li>
<li> Utilização do encapsulamento, deixando os atributos privados e criando os getters e setters para acessar e modificar os atributos.</li>
<li> Criação de dois métodos sem retorno: curte() e reproduz(), que irão incrementar as variáveis totalCurtidas e totalReproducoes, respectivamente.</li>
<li> Organização do código em pacotes.</li>
<li> Criação de uma classe Musica estendendo de Audio, com os atributos adicionais album, cantor e genero.</li>
<li> Criação de uma classe Podcast estendendo de Audio, com os atributos adicionais apresentador e descricao.</li>
<li> Criação de uma classe Principal e instancie um objeto do tipo Musica e outro do tipo Podcast, preenchendo seus atributos;</li>
<li> Criação de um loop para chamar os métodos curte() e reproduz() a fim de simular um número grande de reproduções e curtidas.</li>
<li> Feito uma sobrescrita do método getClassificacao na classe Musica, definindo que se a mesma tiver mais de 2000 reproduções a classificação será 10 e para valores inferiores a classificação será 8.</li>
<li> Feito uma sobrescrita do método getClassificacao na classe Podcast, definindo que se o mesmo tiver mais de 500 curtidas a classificação será 10 e para valores inferiores, a classificação será 7.</li>
<li> Criação uma classe chamada MusicasPreferidas ou apenas Preferencias, com um método sem retorno (void) chamado inclui, que receberá como parâmetro um Audio.</li>
<br>
<br>
<p> No método inclui o polimorfismo, onde foi utilizado o getClassificacao (de acordo com a subclasse que for passada aqui como parâmetro) para exibir alguma mensagem. Para classificação igual ou superior a 9, foi impresso no no terminal uma mensagem e se for inferior, imprime uma outra mensagem. Finalizando instanciando um objeto do tipo MusicasPreferidas ou Preferencias e incluindo a música e podcast instanciados anteriormente</li>
