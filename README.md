# ReFDTestProject
Project containing source code constructs that are used to test the ReFD plug-in for Eclipse.

## Setup
To setup the environment to run the tests do the following:

1. Create a new workspace for Eclipse to execute the tests in. Go to File -> Switch Workspace -> Other. Choose a name and location for your workspace. For example "Test-ReFD-Workspace".

2. Import this ReFDTestProject into the newly created workspace.

3. Switch back to your plug-in development workspace. Go to File -> Switch Workspace -> [your dev workspace].

4. Prepare a run configuration. Go to Run -> Run Configurations. Create or modify a configuration under JUnit Plug-in Test. Make sure to assign the ReFD project containing the testcases and optionally the specific testclass and testmethods to execute.

5. Select JUnit 5 as Test Runner.

6. Open the main tab and assign your newly created workspace to the Location in the Worspace Data section. Make sure to uncheck 'Clear' to make sure the ReFDTestProject remains available in the workspace after testing.
7. Run your tests.
