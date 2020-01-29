# Testes-Python
Testes de automação em Python usando o Selenium

from selenium import webdriver
from selenium.webdriver.common.keys import Keys
import time

driver = webdriver.Chrome(executable_path="C:\ChomeDriverWin32\chromedriver.exe")

driver.get("https://web.whatsapp.com/") 

print (driver.title)

time.sleep(5)

driver.close() # fecha o browser
