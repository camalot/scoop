# 📦 camalot Chocolatey Feed

Welcome to camalot's personal [Chocolatey](https://chocolatey.org/) package feed. This repository hosts a simple-folder NuGet feed for applications not (yet) published to the community Chocolatey.org repository.

## 🚀 How to Install from camalot's Chocolatey Feed

Chocolatey simple-folder feeds are read from a local path, so clone this repository first, then add it as a source:

```shell
git clone https://github.com/camalot/scoop
choco source add --name="camalot" --source="%cd%\scoop\chocolatey"
```

Once the source is added, you can install any of the packages listed below:

## 🛠️ Packages

<table>
  <thead>
    <tr>
      <th>Package</th>
      <th>Description</th>
      <th>Version</th>
      <th>License</th>
      <th>Manifest</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong><a href="https://github.com/camalot/xget">xget</a></strong></td>
      <td>xget is a tool for downloading binaries from the GitHub releases.</td>
      <td><code>2.1.2</code></td>
      <td></td>
      <td><a href="chocolatey/c/camalot/xget/2.1.2/xget.nuspec">nuspec</a></td>
    </tr>
    <tr>
      <td colspan="5">
        <pre><code>choco install xget --source="camalot"</code></pre>
      </td>
    </tr>
  </tbody>
</table>
