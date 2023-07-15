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
