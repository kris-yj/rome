# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2018 > object-rest-spread > 26`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2018/object-rest-spread/26/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2018/object-rest-spread/26/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Expected an identifier"}]}
			}
			location: Object {
				filename: "es2018/object-rest-spread/26/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 18
					line: 1
				}
				start: Object {
					column: 18
					line: 1
				}
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "test"
				loc: Object {
					filename: "es2018/object-rest-spread/26/input.js"
					identifierName: "test"
					end: Object {
						column: 13
						line: 1
					}
					start: Object {
						column: 9
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2018/object-rest-spread/26/input.js"
				end: Object {
					column: 25
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			body: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "es2018/object-rest-spread/26/input.js"
					end: Object {
						column: 25
						line: 1
					}
					start: Object {
						column: 23
						line: 1
					}
				}
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2018/object-rest-spread/26/input.js"
					end: Object {
						column: 22
						line: 1
					}
					start: Object {
						column: 13
						line: 1
					}
				}
				params: Array [
					JSBindingObjectPattern {
						loc: Object {
							filename: "es2018/object-rest-spread/26/input.js"
							end: Object {
								column: 21
								line: 1
							}
							start: Object {
								column: 14
								line: 1
							}
						}
						meta: JSPatternMeta {
							optional: undefined
							typeAnnotation: undefined
							loc: Object {
								filename: "es2018/object-rest-spread/26/input.js"
								end: Object {
									column: 21
									line: 1
								}
								start: Object {
									column: 14
									line: 1
								}
							}
						}
						rest: JSBindingIdentifier {
							name: ""
							loc: Object {
								filename: "es2018/object-rest-spread/26/input.js"
								identifierName: ""
								end: Object {
									column: 19
									line: 1
								}
								start: Object {
									column: 18
									line: 1
								}
							}
						}
						properties: Array [
							JSBindingObjectPatternProperty {
								key: JSStaticPropertyKey {
									value: JSIdentifier {
										name: ""
										loc: Object {
											filename: "es2018/object-rest-spread/26/input.js"
											identifierName: ""
											end: Object {
												column: 20
												line: 1
											}
											start: Object {
												column: 19
												line: 1
											}
										}
									}
									loc: Object {
										filename: "es2018/object-rest-spread/26/input.js"
										end: Object {
											column: 20
											line: 1
										}
										start: Object {
											column: 19
											line: 1
										}
									}
								}
								value: JSBindingIdentifier {
									name: ""
									loc: Object {
										filename: "es2018/object-rest-spread/26/input.js"
										identifierName: ""
										end: Object {
											column: 20
											line: 1
										}
										start: Object {
											column: 19
											line: 1
										}
									}
								}
								loc: Object {
									filename: "es2018/object-rest-spread/26/input.js"
									end: Object {
										column: 20
										line: 1
									}
									start: Object {
										column: 19
										line: 1
									}
								}
							}
						]
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```

 es2018/object-rest-spread/26/input.js:1:18 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected an identifier

    function test({...[]}) {}
                      ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
