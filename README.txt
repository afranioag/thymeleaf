Este projeto é um projeto WEB spring usando o thymeleaf para paginas.

Versões:
* Java 11
* Spring 2.6.7

Gerenciador de dependencias:
* Gradle

Dependencias:
* Spring Web
* DevTools
* Lombok
* Thymeleaf
* WebJars

Para estilo das paginas está sendo utilizado bootStrap usando as bibliotecas do webjars.
--> deve ser adicionado esse webJars para versões do spring igual ou superior a 2.0.0
**	implementation group: 'org.webjars', name: 'webjars-locator-core', version: '0.50'
**	implementation group: 'org.webjars', name: 'bootstrap', version: '4.0.0'
**	implementation group: 'org.webjars', name: 'jquery', version: '3.3.1-1'
**	implementation group: 'org.webjars.bower', name: 'jquery-mask-plugin', version: '1.14.13'
**	implementation group: 'org.webjars.bower', name: 'open-iconic', version: '1.1.1'

Também podendo ser escrito dessa forma:
	implementation 'org.webjars:webjars-locator-core'
	implementation 'org.webjars:bootstrap:5.1.3' //Estou usando esta versão do bootstrap
	implementation 'org.webjars:jquery:3.3.1-1'
	implementation 'org.webjars.bower:jquery-mask-plugin:1.14.13'
	implementation 'org.webjars.bower:open-iconic:1.1.1'

Esses webJars foram retirados do site: www.webjars.org

---> Importante: Não esquecer os estilos css na pasta src/main/resources/static (Só para nota: Eu esqueci e passei horas configurando os webjars)


