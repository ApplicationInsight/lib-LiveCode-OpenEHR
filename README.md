# lib-LiveCode-OpenEHR
dev tools for LiveCode developers wanting to work with OpenEHR

This Repository is for LiveCode developers wanting to connect with libEHR

It contains three main elements

1. A LiveCode scriptOnlyStack - see the  [libOpenEHR](/docs/libOpenEHR.md) document for more details

2. A testLibEHR LiveCode stack - see the  [testOpenEHR](/docs/testOpenEHR.md) document for more details

3. A makeLibEHR LiveCode stack - see the [makeOpenEHR](/docs/makeOpenEHR.md) document for more details

When you drop a .txt file created by the testLibEHR app [for the corresponding openEHR template], it reads in metadata about the openEHR template harvested by the testLibEHR app - it uses this data to create a version of the libOpenEHR scriptOnlyStack as well as a 'test harness' LiveCode stack with corresponding metadata in it to the modified libOpenEHR code library - meaning that the test harness will automatically connect to the modified libOpenEHR and use it to connect to the same openEHR template on the same CDR that the testOpenEHR _app_ used.

![alt text](/images/1460346839_seo-marketing-business-finance-0084.png "nice pig")

```
on preOpenStack
  resizeStack
  answer "hello"
end preOpenStack
```
