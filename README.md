# SCRIPT

*Função muteTab*

![image](https://github.com/user-attachments/assets/007c782c-be84-414e-a892-a386ac84af6e)

A função "muteTab" é definida para silenciar todos os elementos de vídeo e áudio na página atual. Ela faz isso selecionando todos os elementos "video" e "audio" usando "document.querySelectorAll" e, em seguida, definindo a propriedade muted desses elementos como "true"

*Execução da Função MuteTab*

![image](https://github.com/user-attachments/assets/0e7b2271-70f6-48e1-9b1f-b26251a192ee)

Esta linha executa a função "muteTab" assim que o script é carregado, silenciando imediatamente todos os elementos de áudio e vídeo na página atual.

*Observador de Mutação*

![image](https://github.com/user-attachments/assets/944061b2-c661-41dc-b853-533d0fa7c848)

Esta parte do código usa a "API MutationObserver" para observar alterações no "DOM". O observador é configurado para monitorar o "document.body" e seus subelementos "subtree: true". Quando novos nós são adicionados ao "DOM, (childList: true), o observador executa a função "muteTab" novamente para garantir que quaisquer novos elementos de áudio ou vídeo também sejam silenciados.

Este script garante que todos os elementos de áudio e vídeo na página atual, bem como quaisquer novos elementos adicionados posteriormente, sejam silenciados.

# BENEFICIOS

O userscript oferece várias vantagens para os usuários que desejam controlar o áudio em suas guias do navegador. Aqui estão alguns dos principais benefícios:

*Silenciamento Imediato*

O script silencia instantaneamente todos os elementos de áudio e vídeo na página atual assim que é carregado. Isso é útil para evitar interrupções ou distrações causadas por sons inesperados.

*Monitoramento Contínuo*

Utiliza a API MutationObserver para observar alterações no DOM. Isso garante que quaisquer novos elementos de áudio ou vídeo adicionados à página também sejam silenciados automaticamente, proporcionando uma experiência de navegação tranquila e sem ruídos.

*Fácil Implementação*

Pode ser facilmente instalado e ativado usando extensões populares de userscript como Tampermonkey ou Greasemonkey. Não requer conhecimentos avançados de programação para ser utilizado.

*Controle Personalizado*

Permite que o usuário tenha controle personalizado sobre o áudio em suas guias do navegador, o que pode ser particularmente útil em ambientes de trabalho, estudo ou qualquer situação em que o silêncio seja necessário.

*Melhoria na Experiência do Usuário*

Ao eliminar ruídos indesejados, o script melhora a experiência geral de navegação, permitindo que os usuários se concentrem melhor no conteúdo que estão visualizando.

O userscript é uma ferramenta simples, mas eficaz, para gerenciar o áudio nas guias do navegador, proporcionando uma experiência de navegação mais controlada e agradável.
