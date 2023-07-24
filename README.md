# AltUnityTester-UnitySampleGame
Test automation in Unity with AltUnityTester

## First Task is 

        [Test]
        public void TestStartButtonLoadsMainScene()
        {
            //Here you can write the test
            altDriver.LoadScene("Start");
            altDriver.FindObject(By.TEXT, "StartButton").Click();
            altDriver.WaitForCurrentSceneToBe("Main");
        }`
### When the start button that comes after the splash screen is clicked, I automate it to direct us to the game scene.

### I installed AltTester Desktop on macOS and iOS devices. I installed explorer for testing. I'm ready to write a case now.
![image](https://github.com/AlperenDirik/AltUnityTester-UnitySampleGame/assets/95375876/261024b8-0fb3-4ce3-a67e-a0260d642143)
