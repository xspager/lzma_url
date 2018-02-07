# LZMA URL

Uses https://github.com/nmrugg/LZMA-JS to compress long texts and generate base64 url to recover the original text


You can grab the base64 encoded from the URL like http://lzma.danielocl.com.br/?encoded=XQAAgAANAAAAAAAAAAAkGUmYbxYCiQqY5z+ow5VITf//dfAAAA== and decompress on the CLI using:

```bash
echo "XQAAgAANAAAAAAAAAAAkGUmYbxYCiQqY5z+ow5VITf//dfAAAA==" | base64 -D | lzma -d -
```
