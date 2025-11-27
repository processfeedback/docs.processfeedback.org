# Classroom announcement

---

Let students know early that you care about their process, not just the final product. Add a note to your course syllabus or send an announcement at the start of the semester. Here is an example you can adapt.

## Understanding your writing process

Some assignments in this course may ask you to share how you completed your work. You might use an online editor that tracks your typing, such as the one provided by Process Feedback. You may also be asked to reflect on your writing journey and share that process with me. Research shows that reflecting on your writing process can enhance critical thinking and metacognition. Assignments with this requirement will include additional instructions. If you have any concerns or questions, please contact me early so I can accommodate your needs.

<style>
.copy-container {
  position: relative;
  background-color: #ecededff;
  border-color: #e1e3e4ff;
}
.copy-button {
  position: absolute;
  bottom: 4px;
  right: 4px;
  padding: 6px 8px;
  font-size: 12px;
  background-color: #e1e3e4ff;
  border: 1px solid #acb0b4ff;
  border-radius: 6px;
  cursor: pointer;
}
.copy-text{
	padding: 10px 20px;
}
.copy-button:hover {
  background-color: #eaeef2;
}
pre {
  margin: 0;
}
</style>

<div class="copy-container">
	<div class="copy-text">
		Some assignments in this course may require you to share the process you followed to complete the assignment. You may need to use an online editor that tracks your typing, such as the one provided by Process Feedback. You may then be asked to reflect on your writing journey and share your writing process with me. Research shows that reflecting on your writing process can enhance critical thinking and metacognition. Assignments with this requirement will include additional instructions. If you have any concerns or questions, please contact me early so I can accommodate your needs.
	</div>
  <button class="copy-button" onclick="copyToClipboard(this)">Copy this Text</button>
</div>

<script>
function copyToClipboard(button) {
  const codeBlock = button.nextElementSibling.innerText;
  navigator.clipboard.writeText(codeBlock).then(() => {
    button.textContent = 'Text Copied!';
    setTimeout(() => button.textContent = 'Copy', 1500);
  });
}
</script>
