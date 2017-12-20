---
title: Contributing to FROSTT
permalink: /contribute/

github: "https://github.com/frostt-tensor/"
github-io: "https://github.com/frostt-tensor/frostt-tensor.github.io/"

---


# Contributing to FROSTT
FROSTT is an open source project that thrives off community contributions.

## FROSTT Development
Want to contribute to the development of this site or its tools? Great! All
development is conducted on [Github]({{page.github}}). Feel free to file an
issue or submit a pull request.

## Tensor Construction
Sparse tensors are constructed from a large variety of data sources. These
sources are often large, unstructured, and noisy. To aid in the construction of
tensors from these data sources, FROSTT has released a tool for parsing
CSV-like data. If your data can be represented as a CSV file, our
`tensor_parser` tool can map features of data (represented as columns) to
tensor modes and handle many of the tedious details such as mapping entities
to contiguous indices, sorting data, and merging duplicate non-zeros,

`tensor_parser` is MIT licensed and can be found on
[GitHub](https://github.com/frostt-tensor/tensor_parser).


## Tensor Submission
If you have a tensor that you would like to see in this collection, please
consider sharing with us. You **must** have the rights to distribute the data.
By sharing your dataset, you acknowledge that the data will become publicly
available.

1. Fork `frostt-tensor.github.io` on [Github]({{page.github-io}}).

2. Copy the provided template `tensor-template.md`
to the `_tensors/` directory. The name of the file will form the URL of the
tensor page. Suppose your new tensor is named Big-Tensor:
`$ cp tensor-template.md _tensors/big-tensor.md`.

3. Fill in as much information as possible about your new tensor.

4. Build your tensor page. If all went well, your tensor should now exist.
Reload your local [FROSTT](http://localhost:4000/tensors/) page and Big-Tensor
should now be available.

5. Once the tensor page is ready, submit a pull request and include a public
link to the tensor data. We will copy the data to our hosting location, update
the links to our own hosting, merge the pull request, and go live!


