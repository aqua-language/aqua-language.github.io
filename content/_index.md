+++
title = "Aqua"
sort_by = "weight"
+++

**Aqua** is a high-level programming language for processing data streams. It is designed to be simple, expressive, efficient and safe. Aqua compiles to dataflow systems such as Apache Flink (Java), and a custom native runtime (Rust).


## Features (Planned)

* Consume and produce streams using different connectors (e.g., Kafka, TCP, files).
* Decode and encode events using different data formats (e.g., CSV, JSON, Avro).
* Interactively create dataflows that transform, filter and aggregate data through concise query syntax.
* Transparently execute programs locally or distributed.
* Execute external Rust, Python and JavaScript code into programs with sandboxing through WebAssembly.

## Installation

<pre><code><span class="unselectable">$ </span><span class="string">cargo</span> <span class="string">install aqua</span> --git https://github.com/aqua-language/aqua
</code></pre>

## Usage

<pre><code>$ <span class="string">aqua</span>
>> print(<span class="string">"Hello world!"</span>);
Hello world!
</code></pre>

## More

* View the specification of Aqua in the [Manual](/Manual.pdf).
