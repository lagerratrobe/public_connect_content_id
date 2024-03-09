## `get_content_types.Rmd`

### Purpose:

Identifies published content on a Connect server that has Sharing set to "Anyone - no login required", aka "Public".  Splits the list into 2 sections, Interactive content such as Shipy apps, APIs, etc and Static content such as RMarkdown and Jupyter notebooks.

### Prerequisites:

This notebook can be published directly to a Connect server from this repo.  If you want to run the code locally or on a Workbench instance, it expects to have the following:

* `connectapi` R package
* `dplyr` R package
* .Renviron file

-------------------------

_NOTE:  Expected .Renviron example below. .Renviron is not needed if you publish this file directly to Connect._

-------------------

```
CONNECT_SERVER=http://posit2:3939
CONNECT_API_KEY=D4PIPavnonURW4uq4A3ye8NIluznwpn4

```


