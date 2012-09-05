#Sublime Text 2 plugins
===

**Compilei neste arquivo uma lista de plugins essenciais para a minha instalação do SublimeText 2**


##Instalando plugins via Package Control
===
Para instalar novos plugins através do Package Control é só seguir os passos:

#####Executa a paleta de comandos

	Cmd + Shift + P
	
#####Package Control: Install Package

	install
	
#####Digitar o nome do plugin
	'Nome do meu plugin'


##Instalando Bundles do Textmate
===
O SublimeText 2 tem compatibilidade com todos os bundles do Textmate, abaixo instruções de como instalar um bundle:

####1. Navegue até o diretório de bundles do SublimeText
	cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/

#####2. Clone o endereço do repositório do Bundle
	git clone '/endereço-do-repositório-git/repositorio.gist' 

##Primeiros passos
===

###1. Fazer um alias para abrir arquivos com o SublimeText via terminal

	sudo ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" /usr/bin/subl

###2. Instalar Package Control
Executar o comando abaixo dentro do `console` do Aplicativo `View > Show Console`

	import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print 'Please restart Sublime Text to finish installation'

*link do repositório:* <http://wbond.net/sublime_packages/package_control/installation> 

###3 Seguir as instruções de uso do Package Control
instruções de uso já descritas anteriormente na seção de instalação de plugins

##Lista de Plugins recomendados
===

1. SublimeCodeIntel
2. Fetch
3. SidebarEnhancements
4. ZenCoding
5. Prefixr
6. LiveReload [Tutorial](http://shoogledesigns.com/blog/blog/2012/07/23/sublime-text-2-package-control-and-livereload/)
7. AutoFileName [Repositório](https://github.com/BoundInCode/AutoFileName)
8. BracketHighlighter

##Bundles recomendados
===

####LESS
	git clone https://github.com/appden/less.tmbundle
	
####HAML
	git clone https://github.com/handcrafted/handcrafted-haml-textmate-bundle.git
