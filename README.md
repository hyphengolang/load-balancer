# Load-Balancer with Go

## Intro

This project is an experiment with load-balancers in Go.

## Reverse Proxy

The underlining workings of a load-balancer is a reverse proxy. I have used the following [tutorial](https://dev.to/b0r/implement-reverse-proxy-in-gogolang-2cp4) as a template for the [reverse](./reverse/main.go) script.

I can modify the response as mentioned in [this question](https://stackoverflow.com/questions/67211744/how-to-implement-http-forwarding-proxy-in-go) & [this blog](https://www.codedodle.com/go-reverse-proxy-example.html).

Another [blog article](https://blog.joshsoftware.com/2021/05/25/simple-and-powerful-reverseproxy-in-go/) that details some of the more
complex actions that can be made, such as modifying the response & request, as well as headers, handling errors and more.

## Load Balancer

This is using a combination of tutorials to accomplish our goal.

I found [this blog](https://medium.com/swlh/proxy-server-in-golang-43e2365d9cbc#:~:text=A%20forward%20proxy%20is%20also,a%20kind%20of%20forward%20proxy.) that gives
a light insight into how to setup a load balancer.
