
# Custom placeholders
Below are the custom placeholders used in this repository. In each set, (1) is the placeholder syntax as it appears in the template, (2) is the preference name in Zotero's about:config, (3) is the Value for that preference. For more details, see [Cat's workflow guide](https://argentinaos.com/zotero-mdnotes/).

1. {{yamlauthorlist}}
2. extensions.mdnotes.placeholder.yamlauthorlist
3. {"content":" \n- \"{{field_contents}}\"","zotero_field":"author","link_style":"no-links","list_separator": "\"\n- \""}


.
1. {{yamlbooktitle}}
2. extensions.mdnotes.placeholder.yamlbooktitle
3. {"content":"BookTitle: \"{{field_contents}}\"","zotero_field":"bookTitle","link_style":"no-links"}

.
1. {{yamlcollections}}
2. extensions.mdnotes.placeholder.yamlcollections
3. {"content":"\"{{field_contents}}\"","zotero_field":"collections","link_style":"no-links","list-separator":","}

.
1. {{yamldate}}
2. extensions.mdnotes.placeholder.yamldate
3. {"content":"\"{{field_contents}}\"","zotero_field":"date","link_style":"no-links"}

.
1. {{yamlitemtype}}
2. extensions.mdnotes.placeholder.yamlitemtype
3. {"content":"\"{{field_contents}}\"","zotero_field":"itemType","link_style":"no-links","list_separator": ", "}

.
1. yamltags
2. extensions.mdnotes.placeholder.yamltags
3. {"content":"n - \"{{field_contents}}\"","zotero_field":"tags","link_style":"no-links","list_separator": "\"\n - \""}

.
1. yamltitle
2. extensions.mdnotes.placeholder.yamltitle
3. {"content":"\"{{field_contents}}\"","zotero_field":"title","link_style":"no-links"}
