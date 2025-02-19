# R_learn

## Installation

To install R on macOS using Homebrew, run:

```bash
brew install r
```

After installing R, you can:
1. Enter the R terminal by typing:
```bash
R
```

2. Install the R language server by running this command in the R terminal:
```r
install.packages("languageserver")
```

3. Install the R extension in your editor:
   - Open the Extensions view (Cmd+Shift+X)
   - Search for "R"
   - Install the "R" extension by REditorSupport

4. Configure R settings:
   - Press Cmd+Shift+P to open the Command Palette
   - Type "Open User Settings (JSON)"
   - Select "Preferences: Open User Settings (JSON)"

5. Add the following R configuration to your settings.json:
```
{
    "r.rterm.option": [
        "--r-binary=/usr/local/bin/R",  // Replace with your R path from Step 1
        "--no-save",                    // Optional: Prevent saving workspaces
        "--no-restore"                  // Optional: Prevent restoring workspaces
    ]
}

6. Running R Scripts
1. Open a new terminal and type `R` to start the R console
2. To run your R script, you can either:
   - Click the "Run" button in the editor
   - Select the code and press Cmd+Enter to run the selected portion
