# Entrar-como-usu-rio-e-cadastrar
Realizando cadastro e logando como usuário para cadastrar e excluir funcionário.


//As inspeções dos elementos para clicar nas areas de textos e escrever

    Metodos metodos = new Metodos();

    By User = By.name("username");  
    By Senha = By.name("pass");
    By clic = By.xpath("/html/body/div/div[2]/div/form/div[6]/button");
    By novofun = By.xpath("/html/body/nav/div/div/ul/li[2]/a");
    By NewFun = By.xpath("/html/body/nav/div/div/ul/li[2]/a");
    By NomeFun = By.name("nome");
    By FunCpf = By.id("cpf");
    By Sexo = By.name("sexo");
    By Admss = By.name("admissão");
    By Cargo = By.name("cargo");
    By Salario = By.name("salario");
    By tpDeContratacao = By.name("tipo-contratacao");
    By Enviar = By.xpath("/html/body/div/div[2]/div/form/div[3]/input");
	
    
    public void menu(String menu) {

	    if (menu.equalsIgnoreCase("Usuario")) {
	    metodos.clicar(User);
	    }else if (menu.equalsIgnoreCase("Senha")) {
	    metodos.clicar(Senha);
		}else if (menu.equalsIgnoreCase("Entre")) {
            metodos.clicar(clic);
		}else if (menu.equalsIgnoreCase("Novo Funcionario")) {
            metodos.clicar(novofun);
		}else if (menu.equalsIgnoreCase("Nome")) {
            metodos.clicar(NomeFun);
		}else if (menu.equalsIgnoreCase("CPF")) {
            metodos.clicar(FunCpf);
		}else if (menu.equalsIgnoreCase("Sexo")) {
            metodos.clicar(Sexo);
		}else if (menu.equalsIgnoreCase("Cargo")) {
            metodos.clicar(Cargo);
		}else if (menu.equalsIgnoreCase("Salario")) {
            metodos.clicar(Salario);
		}else if (menu.equalsIgnoreCase("CLT")) {
            metodos.clicar(tpDeContratacao);
		}else if (menu.equalsIgnoreCase("Enviar")) {
            metodos.clicar(Enviar);
		}else {
			System.out.println("Cadastro Realizado");
		}
    
  }
  
}
