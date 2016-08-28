- Feature Name: foreman_api_v3 as a plugin
- Start Date: 2015-08-25
- RFC PR:
- Issue:

# Summary
[summary]: #summary

Plugin for Foreman API v3, which is based on v2 controllers but uses format according to the [jsonapi.org  specification](http://www.jsonapi.org).

# Motivation
[motivation]: #motivation

To develop an API that is **Flexible, Consisent, Fast**

JSON API is a great solution to not waste hours on reinventing the wheel in terms of your API responses design. It is a great, extensible response standard which can save your time - both on the backend side and the client side. Your clients can leverage you’re using an established standard to implement an integration with your API in a cleaner and faster way. [[Source: blog.arkency.com](http://blog.arkency.com/2016/02/how-and-why-should-you-use-json-api-in-your-rails-api/)]


# Detailed design
[design]: #detailed-design

Please refer to [the jsonapi.org foremat](http://jsonapi.org/format/) since API v3 is based on a very detailed specification,

# Drawbacks
[drawbacks]: #drawbacks

None

# Alternatives
[alternatives]: #alternatives

Alternative is roll-your-own API spec based on an in-house convention that is acceptable.

# Unresolved questions
[unresolved]: #unresolved-questions

TBD