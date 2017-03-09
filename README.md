# Automatically Navigating Websites by using Selenium

Opens the BBC home page in Firefox, then clicks on the News tab

![](https://raw.githubusercontent.com/atabegruslan/Java-Selenium-Auto-Surf-Webpage/master/Illustrations/selenium.PNG)

```java
import org.openqa.selenium.By;
import org.openqa.selenium.firefox.FirefoxDriver;

public class crawl {
	public static void main(String[] args){
		FirefoxDriver navigator = new FirefoxDriver();
		navigator.get("http://www.bbc.com/");
		navigator.findElement(By.linkText("News")).click();
	}
}				
```
