# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > explicit-inexact-object > explicit_inexact_forbidden_in_exact`

```javascript
Program {
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 40
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentLine {
      id: '0'
      value: '@flow'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 7
          index: 7
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Explicit inexact syntax cannot appear inside an explicit exact object type'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 28
          index: 36
          line: 2
        }
        start: Object {
          column: 29
          index: 37
          line: 2
        }
      }
    }
  ]
  body: Array [
    TypeAliasTypeAnnotation {
      id: BindingIdentifier {
        name: 'T'
        loc: Object {
          filename: 'input.js'
          identifierName: 'T'
          end: Object {
            column: 6
            index: 14
            line: 2
          }
          start: Object {
            column: 5
            index: 13
            line: 2
          }
        }
      }
      typeParameters: undefined
      leadingComments: Array ['0']
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 31
          index: 39
          line: 2
        }
        start: Object {
          column: 0
          index: 8
          line: 2
        }
      }
      right: FlowObjectTypeAnnotation {
        exact: true
        inexact: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 31
            index: 39
            line: 2
          }
          start: Object {
            column: 9
            index: 17
            line: 2
          }
        }
        properties: Array [
          FlowObjectTypeProperty {
            kind: 'init'
            key: Identifier {
              name: 'foo'
              loc: Object {
                filename: 'input.js'
                identifierName: 'foo'
                end: Object {
                  column: 15
                  index: 23
                  line: 2
                }
                start: Object {
                  column: 12
                  index: 20
                  line: 2
                }
              }
            }
            value: NumberKeywordTypeAnnotation {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 23
                  index: 31
                  line: 2
                }
                start: Object {
                  column: 17
                  index: 25
                  line: 2
                }
              }
            }
            optional: false
            proto: false
            static: false
            variance: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 23
                index: 31
                line: 2
              }
              start: Object {
                column: 12
                index: 20
                line: 2
              }
            }
          }
          FlowObjectTypeSpreadProperty {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 28
                index: 36
                line: 2
              }
              start: Object {
                column: 25
                index: 33
                line: 2
              }
            }
            argument: MixedKeywordTypeAnnotation {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 28
                  index: 36
                  line: 2
                }
                start: Object {
                  column: 29
                  index: 37
                  line: 2
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```
