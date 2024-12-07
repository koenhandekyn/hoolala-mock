---
title: 'Add Document'
---
<style>
  form {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  input[type="file"],
  button {
    margin: 1em;
    width: 75%;
  }
</style>
<form method="get" action="{{< ref "pages/point_kitchen.md" >}}" >
  <input type="file" accept="image/*" onchange="this.form.submit()">
  <button type="submit" style="display:none;">Upload</button>
</form>
