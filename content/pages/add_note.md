---
title: 'Add Note'
---
<style>
  form {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  input[type="file"],
  button {
  }
  textarea {
    width: 95%;
    height: 45em;
  }
</style>
<form method="get" action="{{< ref "pages/point_kitchen.md" >}}" >
  <textarea name="note"></textarea>
  <button type="submit">Upload</button>
</form>
