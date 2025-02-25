# Variable Assigner

The Variable Assigner node serves as a hub for collecting branch outputs within the workflow, ensuring that regardless of which branch is taken, the output can be referenced by a single variable. The output can subsequently be manipulated by nodes downstream.

<figure><img src="https://langgenius.feishu.cn/space/api/box/stream/download/asynccode/?code=YWFlNDlhZWRmN2U5NmI1MzIyNzcwNDIxOGRjNmFmMjVfV29TVmt0SHdMdjlXRGR2TFdGdFdraGV2SFIxWmt3OFpfVG9rZW46WVJKZ2I5a1Ztb0RMRnp4ZnpQZGN5Z1Y5bnliXzE3MTI1OTc2NDg6MTcxMjYwMTI0OF9WNA" alt=""><figcaption></figcaption></figure>

Variable Assigner supports multiple types of output variables including `String`,`Number`, `Object`, and `Array`. Given the specified output type, you may add input variables from the dropdown list of variables to the node. The list of variables is derived from previous branch outputs and autofiltered based on the specified type.

<figure><img src="https://langgenius.feishu.cn/space/api/box/stream/download/asynccode/?code=MmQ5OGY3OTBiZjdkYjUzM2M4ODBmMWFmYTc0YzUwMzJfY0JJWkJBcWd1WlVXQTJ4RW56Uk11WE1pOEtZeXN6dzJfVG9rZW46TjA5TGJqWmF4b3VIb3R4eUI4ZWNkUWVkbnNmXzE3MTI1OTc0Mjg6MTcxMjYwMTAyOF9WNA" alt="" width="375"><figcaption></figcaption></figure>

Variable Assigner gives a single `output` variable of the specified type for downstream use.
