# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > module-namespace > body-declare`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
    end: Object {
      column: 0
      index: 45
      line: 4
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    TSModuleDeclaration {
      id: BindingIdentifier {
        name: 'N'
        loc: Object {
          filename: 'input.ts'
          identifierName: 'N'
          end: Object {
            column: 19
            index: 19
            line: 1
          }
          start: Object {
            column: 18
            index: 18
            line: 1
          }
        }
      }
      declare: true
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 1
          index: 44
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: TSModuleBlock {
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 1
            index: 44
            line: 3
          }
          start: Object {
            column: 20
            index: 20
            line: 1
          }
        }
        body: Array [
          VariableDeclarationStatement {
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 20
                index: 42
                line: 2
              }
              start: Object {
                column: 4
                index: 26
                line: 2
              }
            }
            declaration: VariableDeclaration {
              kind: 'const'
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 20
                  index: 42
                  line: 2
                }
                start: Object {
                  column: 4
                  index: 26
                  line: 2
                }
              }
              declarations: Array [
                VariableDeclarator {
                  id: BindingIdentifier {
                    name: 'x'
                    loc: Object {
                      filename: 'input.ts'
                      end: Object {
                        column: 19
                        index: 41
                        line: 2
                      }
                      start: Object {
                        column: 10
                        index: 32
                        line: 2
                      }
                    }
                    meta: PatternMeta {
                      definite: undefined
                      loc: Object {
                        filename: 'input.ts'
                        end: Object {
                          column: 19
                          index: 41
                          line: 2
                        }
                        start: Object {
                          column: 10
                          index: 32
                          line: 2
                        }
                      }
                      typeAnnotation: NumberKeywordTypeAnnotation {
                        loc: Object {
                          filename: 'input.ts'
                          end: Object {
                            column: 19
                            index: 41
                            line: 2
                          }
                          start: Object {
                            column: 13
                            index: 35
                            line: 2
                          }
                        }
                      }
                    }
                  }
                  init: undefined
                  loc: Object {
                    filename: 'input.ts'
                    end: Object {
                      column: 19
                      index: 41
                      line: 2
                    }
                    start: Object {
                      column: 10
                      index: 32
                      line: 2
                    }
                  }
                }
              ]
            }
          }
        ]
      }
    }
  ]
}
```
