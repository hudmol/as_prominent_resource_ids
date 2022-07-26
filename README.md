
# as_prominent_resource_ids

An ArchivesSpace plugin that makes resource ids more prominent in the staff
interface.

When viewing or editing a resource or one of its components a fixed strip at the
bottom of the browser window (like a status bar) displays the Resource's four
part id and title.

This plugin was developed against ArchivesSpace v2.8.0 and is compatible up to
at least v3.2.0.

**Developed by Hudson Molonglo for The New School Archives and Special Collections.**


## Installation

1.  Download into your `archivesspace/plugins` directory.
2.  Add the plugin to your `config.rb`.


## Configuration

This plugin requires no configuration.


## Templates

This plugin overrides a staff interface template. Check it for changes
when upgrading your ArchivesSpace.

Overridden template:
```
    shared/_breadcrumb.html.erb
```
