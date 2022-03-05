### Fake APIs
You can use these APIs for any purpose...

### How to use
attach file name to the end of the following url

https://ahmed0saber.github.io/Fake-APIs/

for example

https://ahmed0saber.github.io/Fake-APIs/days.json

then fetch it

<pre>
  <code>
    const url = "https://ahmed0saber.github.io/Fake-APIs/days.json"
    const getData = () => {
        fetch(url)
        .then(response => response.json())
        .then(data => {
            console.log(data)
        })
    }
    getData()
  </code>
</pre>


### Multi line strings in JSON
https://www.gun.io/blog/multi-line-strings-in-json
