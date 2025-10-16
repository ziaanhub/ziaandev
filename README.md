fetch('https://api.lanyard.rest/v1/users/123456789012345678')
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error(error));
