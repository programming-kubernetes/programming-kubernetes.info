In this book, [Michael Hausenblas](https://twitter.com/mhausenblas) and [Stefan Schimanski](https://twitter.com/the_sttts)  teach you how to develop cloud native apps with the Kubernetes API. We cover everything from custom resources to `client-go` to operators to custom API servers. A solid understanding of Kubernetes and familiarity with the Go programming language are required to benefit from this book.

As of end of July 2019 the book is available [via Safari](https://learning.oreilly.com/library/view/programming-kubernetes/9781492047094/) and in print, later this year.

All the Go code examples used in the book are available here:

* [cnat](https://github.com/programming-kubernetes/cnat): example custom controller & resources implemented using the `sample-controller`, the Operator SDK, and Kubebuilder.
* [pizza-crd](https://github.com/programming-kubernetes/pizza-crd): example custom resource with conversion and admission webhooks
 * [pizza-apiserver](https://github.com/programming-kubernetes/pizza-apiserver): example custom API server

![book cover](pk.png)
