# Spel
<img width="128" alt="5DC88347-DD5E-4173-93CE-44E377100A1E" src="https://github.com/user-attachments/assets/ba1b6eda-51a9-44bb-b636-87de2e58b652">

To use Spel, select some text and choose 'Spell Check Selection' from Alfred's Universal Actions menu. A list of replacements is shown for each misspelt word. If you want to skip a word, the up arrow key will take you to the bottom of the list, revealing the 'Skip Word' option. When finished, 'Done' will replace the selected text with the corrected text.
Alternatively, holding the option key when first running Spel will automatically replace each word with its 'top hit'. Use this with caution though.

## Language Support
Spel supports multiple languages. You can change the spell checking language in several ways:

1. **Workflow Configuration** - Set a default language in the workflow configuration (click the [Configure Workflow…] button in Alfred's preferences).

2. **Hotkey Modifiers** - Hold ⌘ (Command) when triggering the Universal Action to set the language before spell checking begins.

3. **Mid-Check Language Change** - During spell checking, select 'Set Language' from the list to change the language and regenerate suggestions with the new dictionary. The currently selected language is shown with a ✅ checkmark.

## Dependencies
Spel uses aspell which is available through [homebrew](https://formulae.brew.sh/formula/aspell).


