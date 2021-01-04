---
title: "Data Source Types"
weight: 5
menu:
  cli:
    parent: "cli_guides"
    identifier: "cli_bidirectional_data_sources"
    title: "Bidirectional Data Sources"
---

<div class="bp3-callout">The CLI is in early alpha. Need help getting started, or found a bug? <a href="https://github.com/telemetryjet/telemetryjet-cli/issues/new">Open an Issue</a> on our GitHub repository. We appreciate your patience and early support.
</div>
<br />

Jet can interface with many data source types, including files, serial devices, and software protocols. 

Each data source may produce and/or consume data points. "Inputs" produce data, "Outputs" consume data, and "Bidirectional" data sources do both. For example, a `key-value-file-input` reads data from a file in Key-Value format, and a `key-value-file-output` writes data into a file.

Click each type for more information and usage details.

<table class="bp3-html-table bp3-html-table-bordered bp3-html-table-condensed bp3-html-table-striped" style="width: 100%">
  <thead>
    <tr>
      <th style="width: 100px;">Type</th>
      <th style="width: 100px;">Input/Output/Bidirectional</th>
      <th style="width: 200px;">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/cli/guides/data_sources/console">console</a></td>
      <td>Output</td>
      <td>Write data to the console output.</td>
    </tr>
    <tr>
      <td><a href="/cli/guides/data_sources/key-value-file">key-value-file</a></td>
      <td>Output</td>
      <td>Write data into a text file in Key-Value (<code>key=value</code>) format.</td>
    </tr>
    <tr>
      <td><a href="/cli/guides/data_sources/key-value-serial">key-value-serial</a></td>
      <td>Bidirectional</td>
      <td>Read and write data as Key-Value lines over a serial stream.</td>
    </tr>
  </tbody>
</table>

<br />
This list will expand over time. We're currently working on core data source types, including CSV files and streams.

Need a data source type that is not listed? [Open an Issue](https://github.com/telemetryjet/telemetryjet-cli/issues/new) on the CLI Github suggesting it should be officially supported.