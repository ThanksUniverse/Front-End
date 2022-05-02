		
		#GIT
			##Conceitos de Versionamento
				Histórico
				Controle de versão
				Quem alterou
				O quê alterou
				Quando alterou
				Todos os arquivos
				Evolução contínua
			Ter versões mais estáveis e backups para caso algum problema aconteça no seu código
			Maior previsibilidade, velocidade e segurança enquanto codifica

			Arquivo A -- Versão 1
			Arquivo B -- Versão 1

			## Instalação do Git

			## Criar conta no Github

			## Clonar o projeto
			git clone url('')

			## Commits
				Informações de alteração
					-após testado todo seu código

			### GitFlow
				Fluxo do Git


			#### Comandos:
				Git status: Ver o status de arquivos deletados e apagados
				Git add *: Adicionar todos os arquivos que foram alterados antes de dar o commit
				Git commit -m 'name': Da commit para o Github com o nome entre parênteses
				Git push: Atualiza os arquivos para o github
				Git pull: Puxa atualizações do repositório Github
				Git checkout -b


			##### Branchs
			Ramificações / Versões pararelas do código
				-main / master
					- develop
				-DOD Definition of Done: Critérios de aceite
				
				-versionamento 0.1.x


			### Merge
			Mescla de branchs - Caso assuma direto você estará assumindo qualquer erro que possa acontecer 
			Possívelmente terá que resolver conflitos de códigos manualmente

			Git merge main (Mesclar código com o qual você está trabalhando)

			Git checkout -b dev (cria uma branch)
			Git checkout master (mudar de branch)

			Git flow init
				Configurar o flow é MUITO importante para começar o desenvolvimento de projetos mais demorados

			Git flow feature/bugfixes/hotfix start

			Git flow feature finish

			### Pull Request
				Mescla de branchs no repositório
				Permite code review
				O repositório resolve os conflitos automaticamente

			## Configurando o GitFlow
				Git flow init
				Git flow {feature} start {nome-da-feature}
				.gitignore

				Nano - Pasta
				Touch - Criar


				<!--TODO:Lembrar de sempre colocar o responsivo por último e COMEÇAR a utilizar display flex-->