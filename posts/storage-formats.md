# Basic usage

You can select a file format in one of two ways:

1. *Explicitly*, by using the `mv-format` attribute on your Mavo root. Its value is a keyword, depending on the format, e.g. `text`, `markdown`, `csv` etc.
2. *Implicitly*, depending on the extension of your file in mv-storage. E.g. if you use a URL to a CSV file, Mavo will automatically use the CSV format.

Often, you need to specify a different format for the `mv-storage`, `mv-source`, and `mv-init` attributes. You can do this by using the `mv-storage-format`, `mv-source-format`, and `mv-init-format` attributes respectively.

# Available formats

Mavo comes with some formats out of the box, but you can add more via [Plugins](https://plugins.mavo.io/?tag=Format). Read the documentation of the format you’re using carefully, because formats may come with restrictions about the structure of your properties. These restrictions are only about which properties will be used for displaying and saving data. If you have more properties in your Mavo, they will just be ignored. For example, you can have additional properties that are read-only or contain expressions.

Let's add the Mavo logo to check how it will be stored: ![Mavo Logo](https://mavo-powered-blog.netlify.app/posts/images/Mavo_logo.jpg)

![](https://mavo-powered-blog.netlify.app/posts/images/logo.svg)
