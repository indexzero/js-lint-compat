Possible Errors
The following rules point out areas where you might have made mistakes.

| eslint                   | jshint
|:-------------------------|:-------------------------|
| comma-dangle             | es3*
| no-cond-assign           | boss
| no-console               | devel*
| no-constant-condition    | ---
| no-control-regex         |
| no-debugger              | debug
| no-dupe-args             |
| no-dupe-keys             |
| no-duplicate-case        |
| no-empty-character-class |
| no-empty                 | noempty
| no-ex-assign |
| no-extra-boolean-cast |
| no-extra-parens |
| no-extra-semi |
| no-func-assign |
| no-inner-declarations |
| no-invalid-regexp |
| no-irregular-whitespace |
| no-negated-in-lhs |
| no-obj-calls |
| no-regex-spaces |
| no-sparse-arrays | elision
| no-unreachable |
| use-isnan |
| valid-jsdoc |
| valid-typeof |
| no-unexpected-multiline |

Best Practices
These are rules designed to prevent you from making mistakes. They either prescribe a better way of doing something or help you avoid footguns.

| eslint            |
|:------------------|
| accessor-pairs |
| block-scoped-var |
| complexity |
| consistent-return |
| curly |
| default-case |
| dot-notation |
| dot-location |
| eqeqeq |
| guard-for-in |
| no-alert |
| no-caller |
| no-div-regex |
| no-else-return |
| no-empty-label |
| no-eq-null |
| no-eval |
| no-extend-native |
| no-extra-bind |
| no-fallthrough |
| no-floating-decimal |
| no-implicit-coercion |
| no-implied-eval |
| no-invalid-this |
| no-iterator |
| no-labels |
| no-lone-blocks |
| no-loop-func |
| no-multi-spaces |
| no-multi-str |
| no-native-reassign |
| no-new-func |
| no-new-wrappers |
| no-new |
| no-octal-escape |
| no-octal |
| no-param-reassign |
| no-process-env |
| no-proto |
| no-redeclare |
| no-return-assign |
| no-script-url |
| no-self-compare |
| no-sequences |
| no-throw-literal |
| no-unused-expressions |
| no-useless-call |
| no-void |
| no-warning-comments |
| no-with |
| radix |
| vars-on-top |
| wrap-iife |
| yoda |

Strict Mode
These rules relate to using strict mode.

| eslint            |
|:------------------|
| strict |

Variables
These rules have to do with variable declarations.

| eslint            |
|:------------------|
| init-declarations |
| no-catch-shadow |
| no-delete-var |
| no-label-var |
| no-shadow-restricted-names |
| no-shadow |
| no-undef-init |
| no-undef |
| no-undefined |
| no-unused-vars |
| no-use-before-define |

Node.js
These rules are specific to JavaScript running on Node.js.

| eslint            |
|:------------------|
| callback-return |
| handle-callback-err |
| no-mixed-requires |
| no-new-require |
| no-path-concat |
| no-process-exit |
| no-restricted-modules |
| no-sync |

Stylistic Issues
These rules are purely matters of style and are quite subjective.

| eslint            |
|:------------------|
| array-bracket-spacing |
| block-spacing |
| brace-style |
| camelcase |
| comma-spacing |
| comma-style |
| computed-property-spacing |
| consistent-this |
| eol-last |
| func-names |
| func-style |
| id-length |
| id-match |
| indent |
| key-spacing |
| lines-around-comment |
| linebreak-style |
| max-nested-callbacks |
| new-cap |
| new-parens |
| newline-after-var |
| no-array-constructor |
| no-continue |
| no-inline-comments |
| no-lonely-if |
| no-mixed-spaces-and-tabs |
| no-multiple-empty-lines |
| no-nested-ternary |
| no-new-object |
| no-spaced-func |
| no-ternary |
| no-trailing-spaces |
| no-underscore-dangle |
| no-unneeded-ternary |
| object-curly-spacing |
| one-var |
| operator-assignment |
| operator-linebreak |
| padded-blocks |
| quote-props |
| quotes |
| semi-spacing |
| semi |
| sort-vars |
| space-after-keywords |
| space-before-blocks |
| space-before-function-paren |
| space-in-parens |
| space-infix-ops |
| space-return-throw-case |
| space-unary-ops |
| spaced-comment |
| wrap-regex |

ECMAScript 6
These rules are only relevant to ES6 environments.

| eslint                 |
|:-----------------------|
| arrow-parens           |
| arrow-spacing          |
| constructor-super      |
| generator-star-spacing |
| no-class-assign        |
| no-const-assign        |
| no-dupe-class-members  |
| no-this-before-super   |
| no-var                 |
| object-shorthand       |
| prefer-arrow-callback  |
| prefer-const           |
| prefer-spread          |
| prefer-reflect         |
| prefer-template        |
| require-yield          |

Legacy
The following rules are included for compatibility with JSHint and JSLint. While the names of the rules may not match up with the JSHint/JSLint counterpart, the functionality is the same.

| eslint         |
|:---------------|
| max-depth      |
| max-len        |
| max-params     |
| max-statements |
| no-bitwise     |
| no-plusplus    |
