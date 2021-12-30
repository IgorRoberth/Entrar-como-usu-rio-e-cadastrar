# Entrar-como-usu-rio-e-cadastrar
Realizando cadastro e logando como usuário para cadastrar e excluir funcionário.


public class Browsers {

	       //Primeiro passo para realizar a abertura do navegador
	
	protected static WebDriver driver;
	
	public void abrirNavegador(String site) {
		
		try {
			System.setProperty("webdriver.chrome.driver", "C:\\Driver\\chromedriver.exe");
			driver = new ChromeDriver();
			driver.get(site);
			driver.manage().window().maximize();

		} catch (Exception e) {
			System.err.println("-----erro ao abrir navegador-----" + e.getMessage());
			System.err.println("-----causa do erro-----" + e.getMessage());
		}
	}
	
}
