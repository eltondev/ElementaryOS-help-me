
1 - Baixe o zip para OSX > http://www.rodsbooks.com/refind/getting.html (Use o arquivo binário).

2 - Extraia e executa install.sh (no OSX)

3 - Use Utilitário de Disco no (OSX) para redimensionar a sua partição HFS+, em seguida crie uma partição para o ElementaryOS (criae duas partições caso queira uma swap, mas só faça se tiver certeza que está fazendo, em breve escreverei algo sobre partições GNU/Linux). 

4 - Escolha qualquer tipo de partição (não importa, porque iremos substituí-las mais tarde).

5 - Download da imagem iso no site https://elementary.io/pt_BR/ grave em um DVD ou Pendrive.

6 - Reinicie o computador e mantenha pressionada a tecla OPÇÃO depois de ouvir o BIPE para iniciar o Gerenciador de Inicialização

6 - Insira PENDRIVE, selecione ElementaryOS para iniciar a instalação.

7 - Na tela de particionamento, selecione particionamento manual, selecione a partição que você criou no Utilitário de Disco (e swap caso tenha criado)

8 - Na instalação do GRUB ele mesmo irá detectar o sistema EFI e instalar o carregador de inicialização para a partição EFI no /dev/sda1 (pode variar de caso para caso)

9 - Abra agora um cerveja, beba bem devagar, e espere a mágica acontecer (claro, vocês deve saber instalar o eOS assim como qualquer outro sistema, em breve escreveremos um tuto sobre isso), retire o USB.

10 - O rEFInd irá carregar e mostrar para você Entre OSX ou ElementaryOS!

11 - Beijo do magrão!
