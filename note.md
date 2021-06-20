## bootCND



<div>
    <ol>
        {{#student}}
        <li>
            学生{{item.name}}的爱好是
            <ol>
                {{#item.hobby}}
                <li>{{.}}</li>
                {{/item.hobby}}
            </ol>
        </li>
        {{/student}}
    </ol>
</div>

0: (2) ["text", "\n    <div>\n        <ol>\n            "]
1: (3) ["#", "student", Array(4)]
2: (2) ["text", "\n            <li>\n                学生"]
3: (2) ["name", "item.name"]
4: (2) ["text", "的爱好是\n                <ol>\n                    "]
5: (3) ["#", "item.hobby", Array(3)]
6: (2) ["text", "\n                    <li>"]
7: (2) ["name", "."]
8: (2) ["text", "</li>\n                    "]
9: (2) ["/", "item.hobby"]
10: (2) ["text", "\n                </ol>\n            </li>\n            "]
11: (2) ["/", "student"]
12: (2) ["text", "\n        </ol>\n    </div>\n    "]

