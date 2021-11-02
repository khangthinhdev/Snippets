{
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
