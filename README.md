# TC3 - Read and Edit File

Este exemplo descreve um programa que faz a leitura de um arquivo de texto e edita a linha informada na entrada do Function Block. O texto desta linha é substituido pelo texto informado na entrada:

fbEditLineInFile(
	sFilePath:= sFilePath,  //CAMINHO ONDE ESTA O ARQUIVO DE TEXTO .TXT
	nLineToEdit:= 10,       //NUMERO A LINHA A SER EDITADA
	sNewContent:= sNewText, //TEXTO QUE SERA INSERIDO NA LINHA INDICADA SUBSTITUINDO O TEXTO ORIGINAL
	bStart:= bStart,        //PULSO PARA REALIZAR A ESCRITA. UMA NOVA ESCRITA SERA REALIZADA APOS UM NOVO PULSO
	bDone=> ,               //BIT DE CONCLUIDO
	bBusy=> ,               //BIT DE OCUPADO
	bError=> bError,        //BIT DE ERRO
	nErrorId=> nErrorId);   //CODIGO DO ERRO




  CODIGOS DE ERRO:
  

![Uploading image.png…]()
