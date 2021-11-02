{
	// Place your snippets for cpp here. Each snippet is defined under a snippet name and has a prefix, body and
	// description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
	// $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the
	// same ids are connected.
	// Example:
	// "Print to console": {
	// 	"prefix": "log",
	// 	"body": [
	// 		"console.log('$1');",
	// 		"$2"
	// 	],
	// 	"description": "Log output to console"
	// }
	"Intro": {
		"prefix": "intro",
		"body": [
			"#include <iostream>",
			"#include <bits/stdc++.h>",
			"#include <algorithm>",
			"#include <string>",
			"#include <math.h>",
			"$1",
			"",
			"#define ll long long",
			"#define vint vector<int>",
			"#define vlong vector<long>",
			"using namespace std;",
			"",
			"${0:/* code */}"
		]
	},
	"For loop": {
		"prefix": "flop",
		"body": ["for (int $1 = $2; $3; $4)", "{", "\t$0", "}"]
	},
	"While loop": {
		"prefix": "wlop",
		"body": ["while ($1) {", "\t$0", "}"]
	},
	"Main function": {
		"prefix": "mainfunc",
		"body": ["int main()", "{", "\t$0", "\treturn 0;", "}"]
	},
	"Function": {
		"prefix": "func",
		"body": ["${1:int} ${2:name}($3)", "{", "\t$0", "}"]
	}
}
