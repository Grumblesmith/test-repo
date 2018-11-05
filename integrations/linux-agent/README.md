# Linux Agent

Using the Linux Agent, you can quickly deploy and collect metrics with a rich set of metadata.

The agent discovers and collects KPI metrics, integrates with CloudWatch, and can leverage other agent metrics. Using various plugins, the Linux Agent can also pull metrics from many different products running on a Linux operating system \(in addition to pulling metrics from the host Linux OS\).

**Dependencies**

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>OS</b>
      </th>
      <th style="text-align:left"><b>Linux Agent</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <ul>
          <li>Redhat 6 and 7</li>
          <li>CentOS 6 and 7</li>
          <li>Amazon Linux (latest)</li>
          <li>Ubuntu 12, 14, 15, and 16</li>
          <li>Debian 7, 8, and 9</li>
        </ul>
      </td>
      <td style="text-align:left">
        <ul>
          <li><b>CPU: </b><code>/proc/stat</code>
          </li>
          <li><b>Diskspace: </b><code>/proc/mounts</code>
          </li>
          <li><b>Disk Usage: </b><code>/proc/diskstats</code>
          </li>
          <li><b>Load Average: </b><code>/proc/loadavg</code>
          </li>
          <li><b>Memory: </b><code>/proc/stat</code>
          </li>
          <li><b>Network: </b><code>/proc/net/dev</code>
          </li>
          <li><b>VM Stat: </b><code>/proc/vmstat</code>
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>**Upgrading the Linux Agent**

To get the most up-to-date features and bug fixes, update your linux agent when new versions are released. See the [Upgrading the Linux Agent](http://54.172.193.4:8080/books/linux-agent/page/upgrading-the-linux-agent) page for detailed steps. 

