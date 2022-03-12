# Tailwind - usos e aplicações com cdn

<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />

Acesse o site: https://edulonde.github.io/tailwind-cdn-examples/

### Objetivo
Demonstrar os conceitos de utility-first com as classes do Tailwind  via cdn.

### Metodologia
  
Todo estilo do site e exemplos foi feito utilizando apenas com Tailwind via script [cdnjs](https://cdnjs.com).
Não foi necessário escrever nenhuma linha de CSS, isso não quer dizer que não foi necessário conhecer CSS.

O que o Tailwind faz é oferecer classes extremamente úteis, com padrões de cores,comportamentos, tamanhos pré-definidos, e você as aplica livremente em suas tags html. 

Mesmo assim para usar minimamente bem o tailwind é preciso conhecer bem o modelo de caixas do css.

### Exemplo de uso

```html

<!-- acesse o tailwind via cdn dentro da tag <head> -->

<head>
     <script src="https://cdn.tailwindcss.com"></script>
  </head>

<!-- crie um container alinhado ao centro-->
<div class="container h-full flex content-center justify-center">

  <!-- crie uma caixa para o texto-->
	<div class="w-2/3 h-96 bg-purple-700 rounded-2xl shadow-xl flex flex-col self-center items-center">

  		<h2 class="mt-20 text-6xl text-purple-200 ">Hello,</h2>
  		
  		  		
  		<p class="m-4 text-right text-4xl text-bold text-purple-50">World of Tailwind!</p>

  
  	</div>
  	
  	
</div>
  
```


### Considerações Finais
O acesso via script cdnjs é ideal para exemplos, rascunhos, documentos rápidos, pois não é preciso instalar absolutamente nada!
Porém, com a instalação via **npm** (Node Package Manager) vocẽ tem acesso a todas as utilidades do Tailwind.
A documentação do tailwind é muito extensa, porém, devido a um ótimo mecanismo de busca dentro do site, encontramos bem rápido o que procuramos. 

Visite a documentação oficial: https://tailwindcss.com/docs/
