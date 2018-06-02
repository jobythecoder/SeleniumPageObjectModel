"# Selenium with PageObjectModel" 
Starting an UI Automation in Selenium WebDriver is NOT a tough task. You just need to find elements, perform operations on it.But with time test suite will grow. As you add more and more lines to your code, things become tough. 
A better approach to script maintenance is to create a separate class file which would find web elements, fill them or verify them. This class can be reused in all the scripts using that element. In future, if there is a change in the web element, we need to make the change in just 1 class file and not 10 different scripts.

This approach is called Page Object Model(POM). It helps make the code more readable, maintainable, and reusable. 
