# text-v2

Text shower v2.

## Take a Shower
```http
GET https://aweirddev.github.io/text-v2?c=…
```
**URL Parameters**:
- `c` – The content. Supports HTML. (Encoded with Base64)

## Examples

Below is an example of "Hello, World!"

> [!NOTE]
> When using HTML tags, remember to quote (`encodeURIComponent`) your base64

```haskell
https://aweirddev.github.io/text-v2?c=SGVsbG8sIFdvcmxkIQ==
```
