


## Server status

<div id="status-insert">Loading...</div>
<script>
  fetch('/_generated/status.html')
    .then(r => r.text())
    .then(html => document.getElementById('status-insert').innerHTML = html);
</script>
