[![Build Status](https://www.travis-ci.org/billyjf/async-http-client-sbt-scala.svg?branch=master)](https://www.travis-ci.org/billyjf/async-http-client-sbt-scala)

# Value BoundRequestBuilder is not a Member of Object com.ning.http.client.AsyncHttpClient

Why does `import com.ning.http.client.AsyncHttpClient.BoundRequestBuilder` fail in Scala but succeeds in Java?

## Re-Create Issue

`sbt test`