# Automation
package popUps;

import org.openqa.selenium.Alert;
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;

import com.vel.config.Configurations;

public class Demo {

	public static void main(String[] args) throws InterruptedException 
	{
		System.setProperty("webdriver.chrome.driver", Configurations.driverPath);
		
		WebDriver driver = new ChromeDriver();
		
		driver.get("https://demoqa.com/alerts");
		
		driver.manage().window().maximize();
		
		Thread.sleep(3000);
		package popUps;

import org.openqa.selenium.Alert;
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;

import com.vel.config.Configurations;

public class Demo {

	public static void main(String[] args) throws InterruptedException 
	{
		System.setProperty("webdriver.chrome.driver", Configurations.driverPath);
		
		WebDriver driver = new ChromeDriver();
		
		driver.get("https://demoqa.com/alerts");
		
		driver.manage().window().maximize();
		
		Thread.sleep(3000);
		
		WebElement btn = driver.findElement(By.xpath("//button[@id='confirmButton']"));
		
		btn.click();
		
		Alert alt = driver.switchTo().alert();
		
		alt.getText();
		
		alt.accept();
		

	}

}

		WebElement btn = driver.findElement(By.xpath("//button[@id='confirmButton']"));
		
		btn.click();
		
		Alert alt = driver.switchTo().alert();
		
		alt.getText();
		
		alt.accept();
		

	}

}
