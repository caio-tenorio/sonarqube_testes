Para rodar os testes do projeto e apresentá-los no sonarqube é necessário ter o Docker instalado.

Com o docker instalado rode: docker run -d --name sonarqube -p 9000:9000 -p 9092:9092 sonarqube
Abra o seu navegador e entre em localhost:9000
Com o Sonarqube rodando clone este projeto: git clone https://github.com/caio-tenorio/sonarqube_testes.git
Na raiz do projeto, rode: gradle sonarqube
As tasks do gradle serão compiladas e o projeto deve aparecer em localhost:9000
