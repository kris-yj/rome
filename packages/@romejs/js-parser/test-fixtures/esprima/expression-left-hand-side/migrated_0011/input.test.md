# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-left-hand-side > migrated_0011`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 30
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 29
          index: 29
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: MemberExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 29
            index: 29
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        property: StaticMemberProperty {
          value: Identifier {
            name: 'solarsystem'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 29
                index: 29
                line: 1
              }
              start: Object {
                column: 18
                index: 18
                line: 1
              }
            }
          }
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 29
              index: 29
              line: 1
            }
            start: Object {
              column: 18
              index: 18
              line: 1
            }
          }
        }
        object: MemberExpression {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 17
              index: 17
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
          object: ReferenceIdentifier {
            name: 'universe'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 8
                index: 8
                line: 1
              }
              start: Object {
                column: 0
                index: 0
                line: 1
              }
            }
          }
          property: StaticMemberProperty {
            value: Identifier {
              name: 'milkyway'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 17
                  index: 17
                  line: 1
                }
                start: Object {
                  column: 9
                  index: 9
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 17
                index: 17
                line: 1
              }
              start: Object {
                column: 9
                index: 9
                line: 1
              }
            }
          }
        }
      }
    }
  ]
}
```