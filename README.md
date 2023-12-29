# O projeto ✨

Foi feito 2 suítes de testes: procedural (amazon_tests.robot) e em gherkin (amazon_tests_gherkin.robot)

Coloca as evidências dos testes dentro da pasta chamada "Resultados":

`$ robot -d resultados amazon_tests.robot `

Substitui o valor de uma variável global

`$ robot -v BROWSER:firefox -d ./resultados amazon_tests.robot`