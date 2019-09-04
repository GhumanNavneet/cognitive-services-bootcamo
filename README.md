# Pre-Requisite:

Once you receive the Lab Environment details after clicking on Launch Lab, perform the following task given below before starting with the main lab guide

1. From File Explorer, open **“ImageProcessing.sln”** which is under **C:\LearnAI-Bootcamp\lab01.1-computer_vision\resources\code\Starting-ImageProcessing**. It may take a while for Visual Studio to open for the first time, and you will have to log in to your account. The account you use to log in should be the same as your Azure subscription account. Note: If your company has two factor authentication, you may not be able to use your pin to log in. Use your password and mobile phone authentication to log in instead.
2. **Validation step**: In the top right corner of Visual Studio, confirm that you see your name and account information.
3. After Visual Studio loads and the solution is open, right-click on **TestCLI** and select **“Set as StartUp Project”**.
4. **Validation step**: **TestCLI** should appear bold in the Solution Explorer.<br/>
`Note: If you get a message that TestCLI is unable to load, right-click on TestCLI and select “Install Missing Features”. This will prompt you to install .Net Desktop Development. Click Install, then Install again. You may get an error because Visual Studio needs to be closed to install updates. Close Visual Studio and then select Retry. It should only take 1-2 minutes to install. Reopen “ImageProcessing.sln”, confirm that you are able to expand TestCLI and see its contents. Then, right-click on TestCLI and select “Set as StartUp Project”.`
5. Right-click on the solution in Solution Explorer and select **“Build Solution”**.
6. **Validation step**: When you build the solution, the only errors you receive are related to **ImageProcessor** in **Program.cs**. You do not need to worry about yellow warning messages.
