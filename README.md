# project-template-unity

A project template with boilerplate code &amp; asstes made specifically not to use precious time on miscellaneous stuff, aka not reinventing the wheel every project.

## FAQ

Q: Why do you use "mainMenuButton.onClick.AddListener(delegate { SceneManager.LoadScene("mainmenu"); });" shinangas instead of doing it through the editor (like a normal human being)?
A: When you work in a team, you usually don't want to fix merge conflicts with Unity scenes, so it's just safer to do most things through code. + It has some advantages. Like not loosing what corresponds to where in the scene when meta files get removed, or other troublesome issues.
