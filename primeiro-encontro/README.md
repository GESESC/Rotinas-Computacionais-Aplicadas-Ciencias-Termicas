# Git e GitHub
## Tutorial Básico

### O que é GIT

O Git é um sistema de controle de versões de arquivos desenvolvida em 2005 por Linus Torvalds para gerenciar o desenvolviento do Kernel Linux. 

A ferramenta realiza um controle rígido das modificações de qualquer arquivo gerenciado por ela, registrando *snapshots* de cada arquivo a cada nova versão adicionada, incluindo não apenas a modificiação, mas também o momento da modificação (registro cronológico) e seu autor, de forma que o sistema também pode ser utilizado para desenvolvimento colaborativo controlado. 

Nas aplicações computacionais destinadas à Engenharia e Ciências, o Git é fundamental não 
apenas para controlar a versão dos *softwares* mas para recupear e ou reverter qualquer 
modificação mal sucedida de um sistema e possibilitar o desenvolvimento colaborativo de 
alguma ferraenta.  

No sistema operacional Windows o Git pode ser acessado via interface gráfica, 
todavia, foi desenvolvido para uso em terminal, de tal forma que neste ambiente
seu uso é muito mais dinâmico e intuitivo. 

### O que é [GitHub](github.com)?
Trata-se de uma plataforma para desenvolvimento versionado de software de foma 
colaborativa que oferece integração total com o Git, espaço de armazenaento e soluções de 
comunicação e gestão de projeto para equipes de desenvolvimento (não estou sendo 
patrocinado, é isso mesmo). 

Atualmente o GutHub pertence a Mycrosoft e é a plataforma do tipo mais utilizada no mundo
com mais de 100 milhões de desenvolvedores, quatro milhões de organizações registradas e 
mais de 300 milhões de repositórios. 

Uma organização no GitHub, nada mais é que um perfil corporativo que pode englobar 
perfís pessoais colaboradores. Os softwares criados nestes ambientes são entendidos 
como pertencentes à organização com a autoria compartilhada pelos desenvolvedores 
envolvidos.

Você pode visitar a organização GESESC visitando este [LINK](https://github.com/GESESC).
Note que atualmente a organização possui 07 membros (aba *People*), um time de 
desenvolvimento ativo (aba *Teams*), dois projetos em desenvolvimento 
(aba *Projects*) e sete repositórios (aba *Repositories*). 

**Instrução:** *Navegue por cada um desses repositórios para se familiarizar com
o ambiente.*

Um repositório é uma unidade de armazenamento de arquivos que compõe um projeto,
na prática trata-se de um diretório que contém todos os arquivos de um
determinado projeto de software, além do histórico de versões de cada um de 
seus compontens.

Um membro de organização ou time nada mais é que um perfil pessoal de um 
usuário do tipo pessoa física ou jurídica. Você pode visitar meu perfil 
pessoal em (AQUI)[https://github.com/ProfLeao].

**Instruções:** 
1. Caso ainda não possua, crie seu perfil pessoal no GITHUB para 
você armazenar sua própria versão (*fork*) deste curso.
2. Se possível, volte ao meu perfil pessoal e me siga meu perfil pessoal e o 
GESESC no GitHub, isto ajudará bastante e nos credenciará a atingirmos as 
credenciais para receber apoio financeiro para nossos projetos. 

#### Primeiro *fork* e *clone*
Nosso curso estará todo disponiibilizado no repositório (Rotinas Computacionais
Aplicada às Ciências Térmicas)
[https://github.com/GESESC/Rotinas-Computacionais-Aplicadas-Ciencias-Termicas]
pertencente ao GESESC. 

Para que tenha sua própria versão do curso, você deve possuir uma cópia pessoal
do repositório em seu perfil pessoal. A ação de criar uma cópia de um 
reposítório se chma *fork*. 

**Instrução:**
Após criar seu perfil crie um *fork* do repositório do curso em seu perfil.
Localize o botão na parte superior direita do repositório entre os botões 
*Watch* e *Star*.

Cada repositório do GitHub possui um endereço único na rede mundial de 
computadores. Este endereço é utilizado, dentre outras coisas, para fazer 
cópias locais (no seu computador pessoal) do repositório, em uma ação 
denominada clonagem. 

Os clones de repositório são feitos com a ferramenta Git instalada no seu 
computador.

**Instruções:**
1. Crie uma pasta para o curso no computador em que estiver trabalhando
(lembre-se de salvá-la na nuvem antes do fim do encontro), localize o 
endereço da basta e o copie. 
2. Abra o terminal do Git e digite `cd ` e então cole o endeço, você acessará 
com o terminal do Git o local onde irá trabalhar. 
3. Faça o clone do seu *fork* no diretório que criou, para isso copie o endereço
`https` do seu repositório clicando no botão verde `<> Code` e copiando 
o endereço que lá aparecer. Então digite no terminal: `git clone <endereço>`.

