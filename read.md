Commands:
=========
	java -jar bin/SoyToJsSrcCompiler.jar --srcs src/template/main.soy --outputPathFormat dist/js/main.js 
	java -jar bin/closure-stylesheets.jar src/css/main.css  --output-file dist/css/main.css

	when-changed src/template/main.soy java -jar bin/SoyToJsSrcCompiler.jar --srcs src/template/main.soy --outputPathFormat dist/js/main.js 
	when-changed src/css/main.css java -jar bin/closure-stylesheets.jar src/css/main.css  --output-file dist/css/main.css