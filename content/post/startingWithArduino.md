+++
author = "Nicolas Michel"
categories = ["Arduino"]
date = "2017-12-26"
description = "Getting Started with an Arduino Uno"
thumbnail = "img/2017/12/arduinoBoard.jpg"
featuredalt = ""
featuredpath = "date"
linktitle = ""
title = "Getting Started with Arduino"
type = "post"
draft = "false"
+++

# My Adventure in Arduino land

This is a paragraph of text about what I did with this board....

Here is a sample of adding a picture hosted on the site itself.
![sample](/img/2017/12/home.jpg)

It's not all that difficult to include links either. For instance
to link to [the arduino site](https://www.arduino.cc).

### Showing some HTML highlighting....

If you need to write some math:
$$ z = r \cdot (\sin{\phi} + \cos{\phi} \cdot i) + \sum_{i=0}^k \frac{1}{i^k}$$

### Markdown overall 

Whenever you wish to __emphasize__, underscores will do.
Double star are **fine too**. 

Markdown [tutorial](https://www.markdowntutorial.com) in case you want
to learn more about that language.... 


### Showing some HTML highlighting....

{{< highlight html >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}

### C++ Highlight

{{< highlight cpp >}}
#include <iostream>
int main() {
  std::cout << "Hello world!" << std::endl;
  return 0;
}
{{< /highlight >}}

### Youtube

The youtube shortcode embeds a responsive video player for YouTube
videos. Only the ID of the video is required, e.g.:

{{< highlight html >}}



https://www.youtube.com/watch?v=w7Ft2ymGmfc
{{< / highlight >}}

{{< youtube w7Ft2ymGmfc >}}
