# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 316`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/uncategorised/316/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/316/input.js"
		end: Object {
			column: 24
			index: 24
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "es2015/uncategorised/316/input.js"
					identifierName: "A"
					end: Object {
						column: 7
						index: 7
						line: 1
					}
					start: Object {
						column: 6
						index: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/uncategorised/316/input.js"
				end: Object {
					column: 24
					index: 24
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2015/uncategorised/316/input.js"
					end: Object {
						column: 24
						index: 24
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "static"
								loc: Object {
									filename: "es2015/uncategorised/316/input.js"
									identifierName: "static"
									end: Object {
										column: 17
										index: 17
										line: 1
									}
									start: Object {
										column: 11
										index: 11
										line: 1
									}
								}
							}
							loc: Object {
								filename: "es2015/uncategorised/316/input.js"
								end: Object {
									column: 17
									index: 17
									line: 1
								}
								start: Object {
									column: 11
									index: 11
									line: 1
								}
							}
						}
						loc: Object {
							filename: "es2015/uncategorised/316/input.js"
							end: Object {
								column: 22
								index: 22
								line: 1
							}
							start: Object {
								column: 10
								index: 10
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "es2015/uncategorised/316/input.js"
								end: Object {
									column: 22
									index: 22
									line: 1
								}
								start: Object {
									column: 20
									index: 20
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: true
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "es2015/uncategorised/316/input.js"
								end: Object {
									column: 19
									index: 19
									line: 1
								}
								start: Object {
									column: 17
									index: 17
									line: 1
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 10
								index: 10
								line: 1
							}
							loc: Object {
								filename: "es2015/uncategorised/316/input.js"
								end: Object {
									column: 17
									index: 17
									line: 1
								}
								start: Object {
									column: 10
									index: 10
									line: 1
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

### `diagnostics`

```
✔ No known problems!

```