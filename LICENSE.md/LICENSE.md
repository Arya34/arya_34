public class LoginPage extends BasePage {

	@FindBy(id = "email")
	private WebElement email;

	@FindBy(id = "password")
	private WebElement password;

	@FindBy(id = "loginButton")
	private WebElement loginButton;
	
	@FindBy(className = "user")
	private WebElement userName;

	public LoginPage(WebDriver driver) {
		super(driver);



