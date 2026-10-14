# Build the Pirate Hat Fabric mod with GitHub Actions

1. Extract this ZIP.
2. Create a new repository on https://github.com/new (a private repository is fine).
3. Upload the *contents* of the `pirate_hat_fabric` folder to the repository root, including the `.github` folder. Make sure `.github/workflows/build.yml` is present in GitHub.
4. Commit the files to the `main` branch.
5. Open the repository's **Actions** tab and select **Build Pirate Hat Fabric Mod**.
6. Click **Run workflow** if it hasn't started automatically.
7. Open the completed workflow run and download the artifact named `pirate-hat-zombie-fabric-jar`.
8. Extract the artifact ZIP. The `.jar` inside `build/libs` is the mod file. Put it in your Minecraft `mods` folder with Fabric Loader and Fabric API for Minecraft 1.21.4.

If the workflow fails, open the failed run, copy the error from the **Build mod** step, and share it so the source can be fixed. A successful workflow is required before a usable JAR exists.
