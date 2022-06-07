So far you've seen how to build a Go web server that routes requests to different functions depending on the requested URL. But what if you want execute some code before and after every request, regardless of the requested URL? For example, what if you wanted to log all requests made to your server, or allow all of your APIs to be callable cross-origin, or ensure that the current user has authenticated before calling the handler for a secure resource? We can do all of these things easily and efficiently using a middleware handler.

Copyright (c) 2022 Seyed Hossein Hosseini Motlagh
