<!DOCTYPE html>
<html>
<head>
  <style>
    table {
      border-collapse: collapse;
    }
    th, td {
      border: 1px solid black;
      padding: 8px;
      text-align: left;
    }
  </style>
</head>
<body>
  <table id="user-table">
    <thead>
      <tr>
        <th>Username</th>
        <th>Email</th>
        <th>Address</th>
        <th>Admin</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Webmaster</td>
        <td>webmaster@example.com</td>
        <td>Demoland 123</td>
        <td>X</td>
      </tr>
      <tr>
        <td>User123</td>
        <td>user123@example.com</td>
        <td>Userplace 321</td>
        <td>-</td>
      </tr>
      <tr>
        <td>AnotherUser222</td>
        <td>anotheruser222@example.com</td>
        <td>AnotherPlace 21</td>
        <td>-</td>
      </tr>
    </tbody>
  </table>
  <form id="user-form">
    <label for="input-username">Username:</label>
    <input type="text" id="input-username" required><br>
    <label for="input-email">Email:</label>
    <input type="email" id="input-email" required><br>
    <label for="input-address">Address:</label>
    <input type="text" id="input-address" required><br>
    <label for="input-admin">Admin:</label>
    <input type="checkbox" id="input-admin"><br>
    <label for="input-image">Image:</label>
    <input type="file" id="input-image"><br>
    <button type="submit" id="submit-data">Submit</button>
  </form>
  <button id="empty-table">Empty Table</button>
  <script>
    document.getElementById('user-form').addEventListener('submit', function(event) {
      event.preventDefault();
      const usernameInput = document.getElementById('input-username');
      const emailInput = document.getElementById('input-email');
      const addressInput = document.getElementById('input-address');
      const adminInput = document.getElementById('input-admin');
      const imageInput = document.getElementById('input-image');
      const username = usernameInput.value;
      const email = emailInput.value;
      const address = addressInput.value;
      const isAdmin = adminInput.checked;
      if (username && email && address) {
        const table = document.getElementById('user-table');
        const tbody = table.getElementsByTagName('tbody')[0];
        let usernameExists = false;
        const rows = tbody.getElementsByTagName('tr');
        for (let i = 0; i < rows.length; i++) {
          const row = rows[i];
          const existingUsername = row.cells[0].textContent;
          if (existingUsername === username) {
            row.cells[1].textContent = email;
            row.cells[2].textContent = address;
            row.cells[3].textContent = isAdmin ? 'X' : '-';
            usernameExists = true;
            break;
          }
        }
        if (!usernameExists) {
          const newRow = tbody.insertRow();
          newRow.innerHTML = `
            <td>${username}</td>
            <td>${email}</td>
            <td>${address}</td>
            <td>${isAdmin ? 'X' : '-'}</td>
          `;
        }
        usernameInput.value = '';
        emailInput.value = '';
        addressInput.value = '';
        adminInput.checked = false;
      }
    });
    document.getElementById('empty-table').addEventListener('click', function() {
      const table = document.getElementById('user-table');
      const tbody = table.getElementsByTagName('tbody')[0];
      while (tbody.firstChild) {
        tbody.firstChild.remove();
      }
    });
  </script>
</body>
</html>
