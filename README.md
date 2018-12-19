# Examples

```bash
# stdin Dockerfile
docker build -t foo . -f-<<EOF
FROM busybox
RUN echo "hello world"
COPY . /my-copied-files
EOF
```
