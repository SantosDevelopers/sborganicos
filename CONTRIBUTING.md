-- Para Contribuir

	01 - Logue com sua conta no GitHub e faça um Fork e do projeto sborganicos.

	02 - clone o repositório em um diretório na sua maquina:
		Ubuntu = "git clone https://github.com/[seuUsuario]/sborganicos sborganicos"

	03 - entre no diretório criado:
		Ubuntu = "cd sborganicos"

	04 - Inicie o git flow (Caso você não tenha ele instalado ou não saiba como acesse o link: https://github.com/nvie/gitflow/wiki/Installation):
		Ubuntu = "git flow init"
		Nota: Mantenha todos os branchs padrões

	-- Passos que se repetem em cada modificação

	05 - Crie uma nova feature branch para fazer uma modificação:
		Ubuntu = "git flow feature start adicionando-meu-nome-no-readme"
		Nota: modifique adicionando-meu-nome-no-readme pelo nome da modificação.

    06 - Ative o virtual env
        Ubuntu = "source venv/bin/activate"

	07 - Faça a modificação (No exemplo o seu nome no campo Contribuições do readme).

    08 - Saia do virtual env
        Ubuntu = "deactivate"

	09 - Adicione a modificação:
		Ubuntu = "git add ."
		Ubuntu = "git commit -m Finished feature"

	10 - junte a modificação ao branch develop
		Ubuntu = "git flow feature finish adicionando-meu-nome-no-readme"
		Nota: modifique adicionando-meu-nome-no-readme pelo nome da modificação.

	11 - crie um release da modificação:
		Ubuntu = "git flow release start 0.0.1"

	12 - finalise o release da modificação:

		Ubuntu = "git flow release finish 0.0.1"

		Nota 2: O Git Flow abre o editor de texto três vezes:

    			Uma para você editar o texto do merge commit relacionado ao merge entre a release branch 0.0.1 e 				a branch master (sugiro para que você deixe o texto padrão deixado pelo Git.);
    			Um para a descrição da tag 0.0.1, que será criada pelo Git Flow para facilitar mudanças de versão 				no software (Descreva exatamente o que foi adicionado e/ou modificado);
    			Uma para você editar o texto do merge commit relacionado ao merge entre a branch master e a 				branch develop (sugiro para que você deixe o texto padrão deixado pelo Git.);

	13 - faça um push:
		Ubuntu = "git push origin master"

	14 - Agora faça um PULL REQUEST
		Vá a sua página no GitHub e clique em "Pull Request", será aberta uma página 			para que você descreva algum comentário, preencha os campos e clique em "send Pull Request".

Agora é só esperar o mantenedor aceita-la ou não.