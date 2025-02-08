# Uncommon HTML Bug: innerHTML and Script Tags

This repository demonstrates an uncommon bug related to using `innerHTML` in HTML to insert content containing script tags.  Directly inserting `<script>` tags via `innerHTML` can lead to unexpected behavior and errors because the browser's parsing and execution mechanisms are disrupted.  This can be a security risk as well.

The `bug.html` file contains the buggy code.  The `bugSolution.html` file provides a corrected version. The solution uses DOM methods to add elements correctly, preventing the potential security risks and execution issues.