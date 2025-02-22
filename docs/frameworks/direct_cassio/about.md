# Direct usage of CassIO

In most cases, CassIO is used within other frameworks, such as LangChain,
as part of the stack to facilitate usage of Cassandra in ML/GenAI workloads.

However, sometimes one may prefer using CassIO directly in their application: for instance, when the data being processed is other than text, or because advanced customization is warranted. This section is devoted to direct usage of CassIO in application code.

!!! info

    Most of the examples in this section can run straight away as Colab notebooks,
    provided you have checked the [pre-requisites](/start_here/#vector-database).
    (check out the
    <img src="/images/colab.png" style="height: 1.4em; vertical-align: middle;"/>
    icon at the top of each page)

    If you prefer to run in local Jupyter, set up the
    [Direct-Cassio Python environment](/frameworks/direct_cassio/setup/) first.

<!-- documentation-oriented quickstarts, to come -->

## Quickstarts

Below is a collection of end-to-end use cases which make use of
CassIO directly.
All of the following examples can run as Colab
notebooks straight away:

- [Sound similarity detection](/frameworks/direct_cassio/sound_similarity_vectors/), through Vector Search. _Includes starting a Web front-end from within the notebook._
