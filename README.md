# Dynamic Content Example

<div id="content">
  <p>Choose an option:</p>
</div>

<button onclick="showContent('option1')">Option 1</button>
<button onclick="showContent('option2')">Option 2</button>
<button onclick="showContent('option3')">Option 3</button>

<script>
function showContent(option) {
  var contentDiv = document.getElementById('content');
  if (option === 'option1') {
    contentDiv.innerHTML = '<p>This is the content for Option 1.</p>';
  } else if (option === 'option2') {
    contentDiv.innerHTML = '<p>This is the content for Option 2.</p>';
  } else if (option === 'option3') {
    contentDiv.innerHTML = '<p>This is the content for Option 3.</p>';
  }
}
</script>
