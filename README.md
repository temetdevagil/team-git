# _Team Git_

Repositório para aprendizado do git, gitflow e suas funcionalidades.

---

Estaremos usando o git flow em nossos futuros projetos, e para isso nosso time precisa se qualificar com tal ferramenta.

Com este repositório, testaremos comandos e funcionalidades da ferramenta e com isso aprender a usar em um projeto 'real-world'

#### _Fluxo de trabalho_ (Geral):

1. Criar a branch de feature:  
   `$git flow feature start feature/nome-da-feature`

2. Codar a nova funcionalidade normalmente

3. Dar `git push` para o Github (Ou feature publish)  
   `$git flow feature publish feature/nome-da-feature`

4. Ao Finalizar, abrir uma `pull request` comparando a branch **develop** com a branch da nova feature

5. Aguarde o code reviewer fazer sua revisão do código  
   _Caso necessário fazer alterações no código, fazer normalmente e dar `git push`_

6. Com a aprovação da `pull request` (merge), acessar a branch local **develop** (`$git checkout develop`) e dar `$git pull`

7. Voltar para a branch da feature (`$git checkout feature/nome-da-feature`) e a finalizar com: `$git flow feature finish feature/nome-da-feature`
