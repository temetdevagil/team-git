# team-git

Repositório para aprendizado do git, gitflow e suas funcionalidades.

---

Estaremos usando o git flow em nossos futuros projetos, e para isso nosso time precisa se qualificar com tal ferramenta.

Com este repositório, testaremos comandos e funcionalidades da ferramenta e com isso aprender a usar em um projeto 'real-world'

#### _OBS_:

1. Developers podem criar features:  
   `$ git flow feature start feature/nome-da-feature`

2. Developers podem publicar features:
   `$ git flow feature publish feature/nome-da-feature`

3. Code reviewers porem fazer code review e autorizar merges

#### _Fluxo de trabalho_:

1. Criar a branch de feature:
   `$ git flow feature start feature/nome-da-feature`

2. Criar o novo código da funcionalidade nova

3. Dar Push para o Github

4. Ao Finalizar a feature, abrir uma pull request comparando a branch _develop_ com a branch da feature

5. O reviewer fazer sua revisão do código

6. Após mudanças na branch feature, dar git push

7. Quando tudo estiver pronto, pode finalizar a branch da feature, e fazer merge:
   `$ git flow feature finish feature/nome-da-feature`

8. Upar a branch _develop_ para o github (Push)
   (O github automaticamente vai macar a pull request como _closed/merged_ quando finalizada)

teste
