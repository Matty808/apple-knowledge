
## Flags
V = Volitale
P = Persistent
S = System
C = Common

<table>
<thead>
    <th>Name</th>
    <th>Description</th>
</thead>
    <tbody>
{% for entry in site.data.nvram %}
    <tr>
        <td>{{ entry.name }}</td>
        <td>{{ entry.description }}</td>
    </tr>
{% endfor %}
    </tbody>
</table>