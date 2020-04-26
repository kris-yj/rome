# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > predicates > 4`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
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
      index: 55
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Spaces between \xb4%\xb4 and \xb4checks\xb4 are not allowed here.'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 20
          index: 20
          line: 1
        }
        start: Object {
          column: 20
          index: 20
          line: 1
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 54
          index: 54
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 54
            index: 54
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'f'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 5
                  index: 5
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 53
                index: 53
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: ArrowFunctionExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 53
                  index: 53
                  line: 1
                }
                start: Object {
                  column: 8
                  index: 8
                  line: 1
                }
              }
              body: BinaryExpression {
                operator: '==='
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 53
                    index: 53
                    line: 1
                  }
                  start: Object {
                    column: 32
                    index: 32
                    line: 1
                  }
                }
                right: StringLiteral {
                  value: 'string'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 53
                      index: 53
                      line: 1
                    }
                    start: Object {
                      column: 45
                      index: 45
                      line: 1
                    }
                  }
                }
                left: UnaryExpression {
                  operator: 'typeof'
                  prefix: true
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 40
                      index: 40
                      line: 1
                    }
                    start: Object {
                      column: 32
                      index: 32
                      line: 1
                    }
                  }
                  argument: ReferenceIdentifier {
                    name: 'x'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 40
                        index: 40
                        line: 1
                      }
                      start: Object {
                        column: 39
                        index: 39
                        line: 1
                      }
                    }
                  }
                }
              }
              head: FunctionHead {
                async: false
                hasHoistedVars: false
                rest: undefined
                returnType: undefined
                thisType: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 32
                    index: 32
                    line: 1
                  }
                  start: Object {
                    column: 8
                    index: 8
                    line: 1
                  }
                }
                predicate: FlowInferredPredicate {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 28
                      index: 28
                      line: 1
                    }
                    start: Object {
                      column: 20
                      index: 20
                      line: 1
                    }
                  }
                }
                params: Array [
                  BindingIdentifier {
                    name: 'x'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 31
                        index: 31
                        line: 1
                      }
                      start: Object {
                        column: 32
                        index: 32
                        line: 1
                      }
                    }
                    meta: PatternMeta {
                      optional: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 31
                          index: 31
                          line: 1
                        }
                        start: Object {
                          column: 32
                          index: 32
                          line: 1
                        }
                      }
                      typeAnnotation: MixedKeywordTypeAnnotation {
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 17
                            index: 17
                            line: 1
                          }
                          start: Object {
                            column: 12
                            index: 12
                            line: 1
                          }
                        }
                      }
                    }
                  }
                ]
              }
            }
          }
        ]
      }
    }
  ]
}
```