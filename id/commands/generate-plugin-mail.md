# generate:plugin:mail
Generate a plugin mail

**Usage:**
```
drupal generate:plugin:mail [options]
gpm
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--services | Memuat servis dari kontainer.

## Examples
* Generate an email plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
