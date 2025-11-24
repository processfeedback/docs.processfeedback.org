# Classroom announcement

---

Students should be informed in advance that you are interested not only in their final product but also in their working process. To do this, include a note in your course syllabus or send an announcement at the beginning of the semester. Here is an example classroom announcement.

### Understanding your writing process

Some assignments in this course may require you to share the process you followed to complete the assignment. You may need to use an online editor that tracks your typing, such as the one provided by Process Feedback. You may then be asked to reflect on your writing journey and share your writing process with me. Research shows that reflecting on your writing process can enhance critical thinking and metacognition. Assignments with this requirement will include additional instructions. If you have any concerns or questions, please contact me early so I can accommodate your needs.

<style>
.copy-container {
  position: relative;
}
.copy-button {
  position: absolute;
  top: 8px;
  right: 8px;
  padding: 4px 8px;
  font-size: 12px;
  background-color: #f6f8fa;
  border: 1px solid #d0d7de;
  border-radius: 6px;
  cursor: pointer;
}
.copy-button:hover {
  background-color: #eaeef2;
}
pre {
  margin: 0;
}
</style>

<div class="copy-container">
  <button class="copy-button" onclick="copyToClipboard(this)">Copy</button>
	Some assignments in this course may require you to share the process you followed to complete the assignment. You may need to use an online editor that tracks your typing, such as the one provided by Process Feedback. You may then be asked to reflect on your writing journey and share your writing process with me. Research shows that reflecting on your writing process can enhance critical thinking and metacognition. Assignments with this requirement will include additional instructions. If you have any concerns or questions, please contact me early so I can accommodate your needs.
</div>

<script>
function copyToClipboard(button) {
  const codeBlock = button.nextElementSibling.innerText;
  navigator.clipboard.writeText(codeBlock).then(() => {
    button.textContent = 'Copied!';
    setTimeout(() => button.textContent = 'Copy', 1500);
  });
}
</script>
