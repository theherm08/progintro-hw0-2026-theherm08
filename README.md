# Check out solution URL
$ cat solution.txt
theherm08.github.io
# Ensure the URL exists
$ curl --output /dev/null --silent --head --fail theherm08.github.io \
&& echo "URL exists" || echo "URL does not exist"
URL exists
