## Version 1.7.3
 * Parsing: Use the harmony parser via the esnext flag in the config (Joel Kemp)
 * validateIndentation: handle breakless case statements (Mike Sherov)

## Version 1.7.2
 * validateIndentation: fix return in switch failure (Mike Sherov)
 * Cast StringChecker maxErrors property to Number the first time (Florian Fesseler)
 * Fix format of --esnext and --max-errors in README (Joe Lencioni)

## Version 1.7.1
 * validateIndentation: fix empty multiline function body regression (Mike Sherov)

## Version 1.7.0
 * validateJSDoc: Deprecate rule (Joel Kemp)
 * Updated google preset (Richard Poole)
 * Add "requireSpaceBeforeBlockStatements" rule into the jquery preset (Oleg Gaidarenko)

 * CLI: Support --esnext to Parse ES6. (Robert Jackson)
 * CLI: Support a --max-errors option to limit the number of reported errors (mdevils)

 * New Rules: (require|disallow)CapitalizedComments (Joel Kemp)
 * New Rules: (require|disallow)SpacesInCallExpression (Mathieu Schroeter)
 * New Rules: (disallow|require)FunctionDeclarations (Nikhil Benesch)
 * New Rules: (require|disallow)PaddingNewLinesInObjects (Valentin Agachi)

 * Implement "only" for parens rule (Oleg Gaidarenko)
 * Simplify "allButNested" option for spaces rule (Oleg Gaidarenko)
 * Implement "except" option for spaces rule (Oleg Gaidarenko)
 * disallowMultipleVarDecl: Strict mode to disallow for statement exception (Joel Kemp)

 * disallowSpaceBeforeObjectKeys: fix parenthesised property value (Jindrich Besta)
 * requireSpaceBeforeObjectValues: fix parenthesised property value (Jindrich Besta)
 * validateIndentation: Allow non-indented "break" in "switch" statement (kevin.destrem)
 * ValidateIndentation: remove array and object indentation validation (Mike Sherov)
 * validateIndentation: Allow the "if" test to be nested. (Jesper Birkestrøm)
 * ValidateIndentation: Relax indentation rules for function expressions. (Mike Sherov)
 * requireCurlyBraces: support the with statement (Joel Kemp)
 * Fix invalid result of findXxxxToken methods when value is provided (Romain Guerin)
 * requireSpaceAfterLineComment: skips msjsdoc comments (Alexej Yaroshevich)

 * Docs: add a table of contents to README (Henry Zhu)
 * Docs: Make version numbers real markdown headers (Alexander Artemenko)

## Version 1.6.2
 * Fix disallowMultipleLineBreaks with shebang line (Nicolas Gallagher)
 * Improve validateParameterSeparator rule (David Chambers)
 * Add rule for parameter separation validation (James Allardice)
 * Add new rules for object values (Vivien TINTILLIER)
 * Docs: add intellij plugin to friendly packages (idok)
 * Support predefined values for another three rules (Joel Kemp)

## Version 1.6.1
 * Airbnb preset (Joel Kemp)
 * Improve crockford preset (Vivien TINTILLIER)
 * Avoid node.js 0.10.x exit code bug for MS Windows (Taku Watabe)
 * Docs: Update packages and extensions sections with new URLs. (Mike Sherov)

## Version 1.6.0
 * Errors: ability to suppress errors via inline comments. (Mike Sherov)
 * Fix Anonymous Functions in google preset (Ayoub Kaanich)
 * Enhance google's preset (Joel Kemp)
 * Add "iterateTokenByValue" method (Oleg Gaidarenko)
 * Node -> Tokens navigation, token list navigation (Marat Dulin)
 * Do not strip json config from comments (Oleg Gaidarenko)
 * maximumLineLength should not be destructive (Oleg Gaidarenko)
 * Use tilde for package definition (Jordan Harband)
 * Improve stdin support (Joel Kemp)
 * Use correct logic for piped input (Joel Kemp)
 * Properly concatenate large files read from stdin (Nikhil Benesch)
 * Add link to the Atom editor plugin for JSCS (Addy Osmani)
 * Setting default tree to empty object (Bryan Donovan)

## Version 1.5.9
 * Binary Rules: Remove colon check from all binary rules (Oleg Gaidarenko)
 * Presets: Add Mr. Doob's Code Style (MDCS) (gero3)
 * Presets: Add Crockford (Timo Tijhof)
 * Google Preset: Add missing constraints (Turadg Aleahmad)
 * Yandex Preset: Remove repeated rule in yandex preset (Benjamin Tamborine)
 * Yandex Preset: updated to be more accurate (ikokostya)
 * New Rules: (require|disallow)NewlineBeforeBlockStatements (cipiripper)
 * New Rules: (require|disallow)AnonymousFunctions (Rachel White)
 * New Rules: (disallow|require)SpacesInFunction (Mike Sherov)
 * CLI: Accepts piped input from stdin (Joel Kemp)
 * CLI: Add --verbose option that adds rule names to error output. (Mike Sherov)
 * Errors: report Esprima parse errors as rule violations. (Mike Sherov)
 * disallowMultipleLineBreaks: fix issues with shebang line (Bryan Donovan)
 * spacesInFunctionExpressions: ignore function declarations. (Mike Sherov)

## Version 1.5.8
 * Errors: include which rule triggered the error in the error output (gero3)
 * requireTrailingComma: Allow single property objects  / arrays to ignore the rule. (Joel Kemp)
 * requireTrailingComma: Avoids false positives from non object/array literal definitions. (Joel Kemp)
 * validateIndentation: fix indentation for non-block `if` that has block `else`. (Mike Sherov)
 * maximumLineLength: Document the required and default values. (Joel Kemp)

## Version 1.5.7
 * Exclude colon from binary rule of yandex preset (Oleg Gaidarenko)
 * wikimedia: Add 'case' and 'typeof' to requireSpaceAfterKeywords (Timo Tijhof)
 * Correct deal with exclusion and extensions (Oleg Gaidarenko)
 * disallowPaddingNewlinesInBlocks: fix false negatives with newline after closing curly. (Iskren Chernev)
 * Include jscs-browser file to npm package (Oleg Gaidarenko)
 * Clarify docs of use of jscs-browser.js (Oleg Gaidarenko)

## Version 1.5.6
 * Correct prebublish script (Oleg Gaidarenko)

## Version 1.5.5
 * Add allowUrlComments to yandex preset (ikokostya)
 * Improve requireMultipleVarDecl rule (Oleg Gaidarenko)
 * Improve fileExtension option (Oleg Gaidarenko)
 * Perform file check by direct reference (Oleg Gaidarenko)
 * Comma not on the same line with the first operand (Oleg Gaidarenko)
 * Simplify doc instruction a bit (Oleg Gaidarenko)
 * Generate "jscs-browser.js" only during publishing (Oleg Gaidarenko)
 * Fix tests for requireSpaceBeforeBinaryOperators (lemmy)

## Version 1.5.4
 * Fix crash caused by multiline case statements that fall through for validateIndentation rule (Mike Sherov)

## Version 1.5.3
 * Add missing rules in jQuery preset (Oleg Gaidarenko)
 * Exclude comma operator from requireSpaceBeforeBinaryOperators rule (Oleg Gaidarenko)
 * Ignore ios instruments style imports (@sebv)
 * Various doc fixes (Christian Vuerings, Timo Tijhof, Oleg Gaidarenko)

## Version 1.5.2
 * Improve binary rule (Oleg Gaidarenko)
 * Fix recursive descend, #445 (Oleg Gaidarenko)

## Version 1.5.1
 * Version bump to address incorrectly published docs (Mike Sherov)

## Version 1.5.0
 * Sticked Operators Rules: Deprecate in favor of more specific rules (Mike Sherov)
 * Update google preset (Oleg Gaidarenko)
 * Update jQuery preset (Mike Sherov)
 * Implement wikimedia preset (Timo Tijhof)
 * Impelement yandex preset (Alexander Tarmolov)
 * Implement fileExtensions option (Joel Brandt)
 * Implement requireYodaConditions rule (Oleg Gaidarenko)
 * Disallow Space After Line Comment: New Rule (Ben Bernard)
 * Require Space After Line Comment: New Rule (Ben Bernard)
 * Implement requireSpacesInsideParentheses (Mikko Rantanen)
 * MaximumLineLength: add ignoreUrlComments option which ignore comments with long urls. (Mike Sherov)
 * requireCamelCaseOrUpperCaseIdentifiers: add option to ignore object properties. (Mike Sherov)
 * MaximumLineLength: provide relaxing option for comments and/or regular expression literals. (Mike Sherov)
 * disallowPaddingNewlinesInBlocks: Count comments as valid tokens. (Joshua Koo)
 * Add new option to maximumLineLength rule (Oleg Gaidarenko)
 * Function expressions ignore getters and setters (Ruben Tytgat)
 * Add "true" as a possible value for binary/unary rules (Oleg Gaidarenko)
 * Improve disallowSpacesInsideObjectBrackets (Oleg Gaidarenko)
 * Improve disallowSpacesInsideArrayBrackets (Oleg Gaidarenko)
 * Improve disallowSpacesInsideArrayBrackets rule (Oleg Gaidarenko)
 * Improve disallowSpacesInsideObjectBrackets rule (Oleg Gaidarenko)
 * Improve disallowQuotedKeysInObjects rule (Oleg Gaidarenko)
 * Improve requireSpacesInsideObjectBrackets rule (Oleg Gaidarenko)
 * Improve handling comments for *SpaceAfterKeywords (Oleg Gaidarenko)
 * Improve requireOperatorBeforeLineBreak (Oleg Gaidarenko)
 * Improve defintions of operators in utils module (Oleg Gaidarenko)
 * Improve requireSpaceBeforePostfixUnaryOperators (Oleg Gaidarenko)
 * Improve disallowSpaceBeforePostfixUnaryOperators (Oleg Gaidarenko)
 * Improve requireSpaceAfterPrefixUnaryOperators (Oleg Gaidarenko)
 * Improve disallowSpaceAfterPrefixUnaryOperators (Oleg Gaidarenko)
 * Improve disallowSpaceAfterBinaryOperators rule (Oleg Gaidarenko)
 * Improve requireSpaceBeforeBinaryOperators rule (Oleg Gaidarenko)
 * Improve disallowSpaceBeforeBinaryOperators rule (Oleg Gaidarenko)
 * Improve requireSpaceAfterBinaryOperators rule (Oleg Gaidarenko)
 * Improve requireOperatorBeforeLineBreak rule (Oleg Gaidarenko)
 * Improve requireSpaceAfterPrefixUnaryOperators rule (Oleg Gaidarenko)
 * Improve requireOperatorBeforeLineBreak rule (Oleg Gaidarenko)
 * Differentiate errors for requireSpaceAfterKeywords (Oleg Gaidarenko)
 * Modify lint options of jshint and jscs (Oleg Gaidarenko)
 * Test Cleanup (Oleg Gaidarenko)
 * Throw error if specified preset does not exist (Oleg Gaidarenko)
 * utils: Remove duplicate '+=' from binaryOperators (Timo Tijhof)
 * Various readme fixes (Syoichi Tsuyuhara)
 * Provide friendly message for corrupted config (Oleg Gaidarenko)
 * Use new Vow API (Jordan Harband)
 * Update Mocha (Jordan Harband)
 * Update dependencies (Jordan Harband)
 * Various improvements to the utils module (Oleg Gaidarenko)
 * "null" must be a quoted key in IE 6-8 (Jordan Harband)
 * Change signature of findOperatorByRangeStart (Oleg Gaidarenko)
 * Add isTokenParenthesis method to token helper (Oleg Gaidarenko)
 * Improve getTokenByRangeStart method (Oleg Gaidarenko)
 * Correct docs for requireSpacesInsideParentheses (Oleg Gaidarenko)
 * readme: Clean up assignment operators (Timo Tijhof)

## Version 1.4.5
 * Hotfix: Fix binary rules for "," and "=" operators (@markelog)

## Version 1.4.4
 * Improve `requireSpaceAfterBinaryOperators` rule (@markelog)
 * Improve `disallowSpaceAfterBinaryOperators` rule (@markelog)
 * Improve `requireSpaceBeforeBinaryOperators` rule (@markelog)
 * Improve `disallowSpaceBeforeBinaryOperators` rule (@markelog)
 * Update google preset (@markelog)
 * Fixes `requirePaddingNewlinesInBlocks`: support multi-line padding (@zz85)
 * Update error message when no config is found (@mikesherov)
 * Rule `requireSpacesInConditionalExpression` (@mikesherov)
 * Rule `disallowSpacesInConditionalExpression` (@mikesherov)
 * Fixes for `validateIndentation` rule: fix more weird onevar constructs and associated indentation rules. (@mikesherov)
 * Fixes for `validateIndentation` rule: fix bug when IfStatement test contains a BlockStatement

## Version 1.4.3:
 * Presets folder was missing in the package (@mdevils).

## Version 1.4.2:
 * Rule `requireSpaceAfterKeywords`: do not fail on linebreaks (@mdevils).

## Version 1.4.1:
 * Rule `disallowPaddingNewlinesInBlocks`: check for comments in the whitespace. Fixes #347 (@mikesherov).
 * Introduce extensions section in README (@zxqfox)
 * Fixes for `validateIndentation` rule: properly validate finally clauses. Fixes #311 (@mikesherov).
 * Fixes for `validateIndentation` rule: tests for holes in array and more complex temporary fix for it (@zxqfox).
 * Fixes for `validateIndentation` rule: allow for extra indents when first variable
   in a declaration is multi-line (@mikesherov).
 * Fixes for `validateIndentation` rule: prevent false positive when array elements are
   on same line as array opener, but array is not single line. Fixes #353 (@mikesherov)
 * Restructuration of lib/test files (@markelog)

## Version 1.4.0:
 * Dropped `node.js` 0.8 support.
 * Update all dependencies to their latest versions except `vow`/`vow-fs` (@XhmikosR).
 * Add dependency status badges (@XhmikosR).
 * Advanced search for the configuration files (@markelog).
 * Improve `requireSpaceAfterKeywords` rule: trigger error if there is more then two spaces (@markelog).
 * Rule `spaceAfterKeywords`: fix up funarg issue (@markelog).
 * Make `requireMultipleVarDecl` rule more like onevar (@markelog).
 * Allow comments in parentheses for rule `disallowSpacesInsideParentheses` (@Famlam).
 * Extract own settings into google preset (@jzaefferer).
 * Rule `disallowTrailingComma` (@rxin).
 * Rule `requireTrailingComma` (@rxin).
 * Rule `disallowSpaceBeforeBlockStatements` (@rxin).
 * Rule `requireSpaceBeforeBlockStatements` (@rxin).
 * Rule `requireBlocksOnNewline` (@mikesherov).
 * Rule `requirePaddingNewlinesInBlock` (@mikesherov).
 * Rule `disallowPaddingNewlinesInBlock` (@mikesherov).

## Version 1.3.0:
 * New JSCS config format: `.jscsrc`. JSON-file with comments.
 * Rule `requireBlocksOnNewline` (@Famlam).
 * Rule `requireSpacesInAnonymousFunctionExpression` (@jamesallardice).
 * Rule `disallowSpacesInAnonymousFunctionExpression` (@jamesallardice).
 * Rule `requireSpacesInNamedFunctionExpression` (@jamesallardice).
 * Rule `disallowSpacesInNamedFunctionExpression` (@jamesallardice).
 * Custom path to reporter (@Adeel).
 * Option `escape` for rule `validateQuote` (@mikesherov).
 * Fixed `validateIndentation` rule (@mikesherov).
 * Fixed `excludeFiles` option (@markelog).
 * CLI/Reporter fixes (@markelog, @am11).
 * Documentation fixes (@tenorok).
 * Minor tweaks (@XhmikosR).

## Version 1.2.4:
 * Fixed typos.
 * Fixed `validateIndentation` rule.
 * Sorting errors.

## Version 1.2.3:
 * New reporter: `inline` (@clochix).
 * Fixed for rule `requireDotNotation` (@ikokostya).

## Version 1.2.2:
 * Fixed case with number for `requireDotNotation` rule (@andrewblond).

## Version 1.2.1:
 * Fix in error message for rule `maximumLineLength` (@pdehaan).

## Version 1.2.0:
 * Rule `requireCommaBeforeLineBreak` (@mikesherov).
 * Rule `disallowCommaBeforeLineBreak` (@mikesherov).
 * Rule `requireDotNotation` (@mikesherov).
 * Rule `requireCamelCaseOrUpperCaseIdentifiers` (@mikesherov).
 * Rule `disallowEmptyBlocks` (@mikesherov).
 * Rule `validateQuoteMarks` (@mikesherov).
 * Rule `requireParenthesesAroundIIFE` (@mikesherov).
 * Rule `requireOperatorBeforeLineBreak` (@mikesherov).
 * Rule `requireCapitalizedConstructors` (@mikesherov).
 * Rule `disallowDanglingUnderscores` (@mikesherov).
 * Rule `disallowTrailingWhitespace` (@mikesherov).
 * Сurly brace checking for 'case' and 'default' statements (@mikesherov).
 * Rule `maximumLineLength` (@mikesherov).
 * Rule `disallowMixedSpacesAndTabs` (@mikesherov).
 * Rule `validateIndentation` (@mikesherov).
 * README: Reformat to use headings (@nschonni).
 * ES3 future reserved words added to tokenIsReservedWord() (@maxatwork).
 * Fixes for: requireSpaceBeforePostfixUnaryOperators, requireSpaceAfterPrefixUnaryOperators,
   disallowSpaceBeforePostfixUnaryOperators, disallowSpaceAfterPrefixUnaryOperators (@mdevils).
 * Rule `disallowMultipleLineStrings` (@mikesherov).

## Version 1.0.15:
 * junit reporter (@markelog).

## Version 1.0.14:
 * Option `additionalRules` (@markelog).
 * disallowQuotedKeysInObjects: Exclusion array (@nschonni).

## Version 1.0.13:
 * Option `validateLineBreaks` (@twoRoger).

## Version 1.0.12:
 * Fixes for jsdoc params.

## Version 1.0.11:
 * Prefix unary rules: `disallowSpaceAfterPrefixUnaryOperators`, `requireSpaceAfterPrefixUnaryOperators` (@mishaberezin).
 * Postfix unary rules: `disallowSpaceBeforePostfixUnaryOperators`, `requireSpaceBeforePostfixUnaryOperators` (@mishaberezin).

## Version 1.0.10:
 * Reporter support — `console`, `text`, `checkstyle`.

## Version 1.0.9:
 * Browser-compatible version.
 * Fix for `disallowMultipleLineBreaks` option to report only once per each sequence of line breaks.
 * Fix for `disallowMultipleLineBreaks` option to work properly when CRLF line break is used.

## Version 1.0.8:
 * Fixes for `safeContextKeyword`.

## Version 1.0.7:
 * Disallow spaces inside parentheses (@ignovak).

## Version 1.0.6:
 * Convert tabs into spaces (@markelog).
 * Report illegal space between nested closing curly braces (@twoRoger).
 * Use absolute path to config when specified (@vtambourine).
 * safeContextKeyword option to check "var that = this" expressions (@doochik).

## Version 1.0.4-1.0.5:
 * Fixed mistype `disallowMulipleVarDecl` -> `disallowMultipleVarDecl`.
 * Fixed error for invalid symlink checking.

## Version 1.0.3:
 * Changed behaviour for `disallowMultipleVarDecl` options. Now accepts multiple var decl in `for` decl.

## Version 1.0.2:
 * Option `requireSpacesInsideArrayBrackets` (@mishanga).

## Version 1.0.1:
 * Not reporting about extra quotes for zero-starting numbers in `disallowQuotedKeysInObjects`.

## Version 1.0.0:
 * Camel-case configuration options.
 * Option `requireAlignedObjectValues`.
 * Option `requireSpaceAfterObjectKeys`.
 * JSDoc for core functions and classes.
 * Fix error position for disallowSpacesInsideObjectBrackets and disallowSpacesInsideArrayBrackets.


## Version 0.0.12:
 * Fix in `disallowSpaceAfterObjectKeys` location reporting.

## Version 0.0.11:
 * Option `disallowSpaceAfterObjectKeys`.
 * Option `disallowSpacesInsideArrayBrackets`.
 * Do not automatically exclude hidden files.

## Version 0.0.10:
 * Fix in `disallowQuotedKeysInObjects`.

## Version 0.0.9:
 * Fix in `disallowQuotedKeysInObjects`.

## Version 0.0.8:
 * Fix in `requireSpacesInsideObjectBrackets`.
 * Option `disallowQuotedKeysInObjects`.

## Version 0.0.7:
 * Option `requireSpacesInsideObjectBrackets`.
 * Option `disallowSpacesInsideObjectBrackets`.

## Version 0.0.6:
 * Fixes incorrent checkPath behavior.

## Version 0.0.5:
 * .jshintrc config.
 * Error message format fixes.

## Version 0.0.4:
 * Option `disallowYodaConditions`.
 * Option `requireMultipleVarDecl`.

## Version 0.0.3:
 * Option `excludeFiles`, which accepts patterns.

## Version 0.0.2:
 * Link to parent nodes.

## Version 0.0.1:
 * Initial implementation.
