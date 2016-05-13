# Flexless

Here at Caktus we love Flexbox! And we love making styling easier with Less,
so we combined two great things. Flexless makes Flexbox less difficult to support
across a wide range of supported browsers.

## Mixins for Containers

### `flex-layout`

Initiate an element as a Flex container, including all the backfilled prefixing necessary:

    .flex-layout();

### `flex-direction`

<pre>flex-direction(<em>direction</em>)</pre>

*direction* can be `row`, `column`, `row-reversed`, or `column-reversed`

### `flex-wrap`

<pre>flex-wrap(<em>option</em>)</pre>

*option* can be `wrap` or `nowrap`

### Others

<pre>justify-content(<em>value</em>)</pre>
<pre>align-items(<em>value</em>)</pre>

Where *value* can be `flex-start`, `flex-end`, `center`, `space-around`, or `space-between`

## Mixins for Items

<pre>flex-basis(<em>value</em>)</pre>
<pre>flex-shrink(<em>value</em>)</pre>
<pre>flex-grow(<em>value</em>)</pre>
