
**

# Esse projeto foi desenvolvimento como parte da Trilha de Estudos dos IrmãosDev e pode ser acessado no link: https://irmaos.dev/trilha/3.html#projeto3

**

Na sequência, seguem as instruções:

## Página web interagindo com CrudCrud

Crie uma página completa, contendo:

 - um campo para colocar o link do CrudCrud que:
	 - ao perder o foco (blur) envia uma requisição de listar todas as pessoas e:
	 - caso registros existam, criar a tabela descrita a baixo;
	 - caso nenhum registro exista, exibir a mensagem: "Nenhuma pessoa cadastrada.";
 - um botão para adicionar pessoas;
 - uma modal que aparece ao clicar nesse botão;
 - um formulário para inserir a pessoa dentro da modal contendo:
	 - text para o Nome e Email;
	 - radio button para o Tipo: Cliente, Fornecedor ou Empregado, que:
		 - deve mapear estes tipos para 1, 2 e 3;
	 - botão para cancelar que fecha a modal;
	 - botão para inserir a pessoa que faz:
	 - valida se todos os campos estão preenchidos;
	 - valida se é um email válido;
	 - envia a requisição para criar a pessoa;
	 - exibe a mensagem de sucesso ou erro;
 - uma tabela que lista todas as pessoas cadastradas e que contém:
	 - o nome de cada coluna (Nome, Email e Tipo);
	 - os dados de cada pessoa em cada linha, onde:
	 - tipo deve ser exibido por extenso, em vez de 1, 2 e 3
	 - um botão de deletar que abre um diálogo de confirmação que faz ao confirmar:
		 - envia a requisição de deletar;
		 - exibe a mensagem de sucesso ou erro;
	 - um botão de editar que abre uma modal que:
		 - conteḿ um formulário de edição, similar ao inserir;
		 - os campos devem estarem preenchidos com os valores da pessoa correspondente;
	 - um botão de cancelar que fecha a modal
	 - um botão de confirmar a edição que:
		 - realiza as mesmas verificações que a inserção;
		 - enviar a requisição de editar;
		 - exibe mensagem de sucesso ou erro.

Como os dados são salvos no CrudCrud, recarregar a página ou fechar e abrir novamente deve exibir os dados atuais.
