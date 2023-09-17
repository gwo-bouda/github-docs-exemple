# Github Docs Exemple

## CodeBlocks

```go
go doc bytes.Buffer
package bytes // import "bytes"

type Buffer struct {
    // Has unexported fields.
}
    A Buffer is a variable-sized buffer of bytes with Read and Write methods.
    The zero value for Buffer is an empty buffer ready to use.

func NewBuffer(buf []byte) *Buffer
func NewBufferString(s string) *Buffer
func (b *Buffer) Bytes() []byte
func (b *Buffer) Cap() int
func (b *Buffer) Grow(n int)
func (b *Buffer) Len() int
func (b *Buffer) Next(n int) []byte
func (b *Buffer) Read(p []byte) (n int, err error)
func (b *Buffer) ReadByte() (byte, error)
```
## TO DO
- [x] Blah
- [x] Bleh
- [x] Blih
## Refs
- [MD complete](https://github.github.com/gfm/)
- [MD Basics](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
