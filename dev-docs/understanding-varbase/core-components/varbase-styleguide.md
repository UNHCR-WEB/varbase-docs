# Varbase Styleguide

Provides custom styling guide for components for Varbase.

## Varbase Styleguide Module

{% hint style="info" %}
Varbase style guide features are bundled through the **Varbase Styleguide** module.  
GitHub: [https://github.com/Vardot/varbase\_styleguide](https://github.com/Vardot/varbase_styleguide)  
Drupal.org: [https://www.drupal.org/project/varbase\_styleguide](https://www.drupal.org/project/varbase_styleguide)

After building a project using the `varbase-project` template, you can see the code of the **Varbase Email** module in:
{% endhint %}

```text
project_directory
|-- docroot
    |-- modules
        |-- contrib
            |-- varbase_styleguide
```

Brings in the following core and contributed modules to your site:

| Module                                         | Purpose |
| :--- | :--- |
| \*\*\*\*[**Style Guide**](https://www.drupal.org/project/styleguide)\*\*\*\* | Generates a theme style guide for proofing common elements. |
| \*\*\*\*[**View Modes Inventory**](https://www.drupal.org/project/vmi)\*\*\*\* | This module has a set of template view modes that we typically use \(some of them\) in each website. |

## Configuration

* Navigate to **Administration \ Extend** and enable the Varbase Styleguide module.
* Navigate to **Administration \ Structure \ Content types** and add a new content type.
* Navigate to **Administration \ Structure \ Content types \ \[Content type to edit\] \ Manage display** and in the vertical tab set select "Custom display settings" and activate desired View modes. Save.
* Navigate to **Administration \ Content \ Add content \ \[Content type to add\]** and add a test node in the new content type.
* Navigate to **Administration \ Appearance \ Styleguide** and search for the name of the content type for an example of what its view modes will look like.

\*\*\*\*



