https://flask.palletsprojects.com/en/3.0.x/#
git config --global user.name "caique325"
git config --global user.email "caique-magalhaes1@outlook.com"

pip 1- preparaçao do ambiente 
	1.1 - Criar o ambiente virtual
		$python -m virtualenv venv
		$pip install virtualenv
 		$pip freeze
		pip install Flask
	 1.1.1 ativando venv\Scripts\activate
	1.2


flask --app mecpy run --debug
salvamento de pacotes : pip freeze>requirements.txt
instalar pacotes salvos : pip install -r requirements.txt