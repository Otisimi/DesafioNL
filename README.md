## Agenda_Python_Django

#### Objetivo:
	Este projeto tem como objetivo criar uma agenda estilo to-do list com Python Django. 
	
	
	
![Screens](https://i.imgur.com/KDryu8r.png "Screens")
	
<hr style="height: 10px;">
##### Login
	Tela de login, com Admin, somente ele pode cadastrar novos usuários
	Agora possui um logo da empresa NL, uma pequena foto de usuário ao lado, e um espaçamento maior entre a caixa de login e senha
	
![image](https://user-images.githubusercontent.com/95048762/143686958-4ad3f014-42dd-4f44-99aa-e4ee375b0c92.png)


### CSS no Django

Para trabalhar com CSS no Django, utilizamos a pasta "static" dentro da pasta Core do projeto.

![core](https://i.imgur.com/q36AdSw.png "core")

Adicionamos o STATICFILES_DIRS no arquivo settings 

![settings](https://i.imgur.com/pz138Yh.png "settings")

No HTML, adicionamos o {% load static %} em cima da tag < link> e no SRC adicionamos {"% static 'caminho' %"}


![load](https://i.imgur.com/cYw8Geq.png "load")

Lista de tarefas (Retificada)

A lista de tarefas agora conta com o local do evento, bem como sua descrição
![image](https://user-images.githubusercontent.com/95048762/143686984-98c7ac2c-97a1-498a-a30f-7688bc1017ee.png)

A tela de cadastro de novo item agora tem, na parte da descrição, uma caixa de texto
para o usuário informar a descrição do evento

![image](https://user-images.githubusercontent.com/95048762/143687012-685f4813-bbeb-4c74-b66a-7cf42bfa5811.png)

Muito obrigado pela atenção!! 🤗
