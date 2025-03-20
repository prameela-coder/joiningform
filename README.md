 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Employee Personal Data Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #a83535;
    }
    .container {
      width: 90%;
      max-width: 800px;
      margin: 20px auto;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
    }
    .logo {
      display: block;
      margin: 0 auto 20px;
      max-width: 150px;
    }
    h2 {
      text-align: center;
      font-style: #5975f0;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    label {
      font-weight: bold;
    }
    input, textarea, select {
      padding: 8px;
      width: 100%;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    textarea {
      resize: none;
    }
    .button-group {
      text-align: center;
    }
    button {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Add your company logo below -->
    <img src="logo.png" alt="Company Logo" class="logo">
    <h2>New Employee Personal Data Form</h2>
    <form id="employeeDataForm">
      
  </div>
  <fieldset>
    <legend>Section 1 - Personal Info</legend>
        <table border="1">
          <tr>
              <th>First Name</th>
              <th>Middle Name</th>
              <th>Last Name</th>
          </tr>
          <tr>
              <td><input type="text" id="first-name" name="first-name" placeholder="First Name" required></td>
              <td><input type="text" id="middle-name" name="middle-name" placeholder="Middle Name"></td>
              <td><input type="text" id="last-name" name="last-name" placeholder="Last Name" required></td>
          </tr>
        </table>
        <label>Blood Group: <input type="text"></label>
        <label>Email: <input type="email" required></label>
        <label>Date of Birth: <input type="date" required></label>
        <label>Father's Name: <input type="text"></label>
        <label>Date of Joining at GGS: <input type="date" required></label>
        <label>Date of Relieving: <input type="date" required></label>
      </fieldset>
      
      <fieldset>
        <legend>Section 2 - Official Info</legend>
        <label>Saving Account No: <input type="text"></label>
        <label>Employee Contact Number: <input type="tel"></label>
        <label>Emergency Contact Number: <input type="tel"></label>
        <label>Bank Name: <input type="text"></label>
        <label>Branch: <input type="text"></label>
        <label>IFSC Code: <input type="text"></label>
        <label>PAN No.: <input type="text"></label>
        <label>Provident Fund(UAN No.): <input type="text"></label>
        <label>Can we create new PF accont Y/N: <input type="text"></label>
        <label>Beneficiary Full Name: <input type="text"></label>
        <label>Aadhar Card No: <input type="text"></label>
        <label>Permanent Address: <textarea rows="3"></textarea></label>
        <label>Present Address: <textarea rows="3"></textarea></label>
      </fieldset>
      
      <fieldset>

        <legend>Section 3 - Education Details</legend>
        <label>Name Of The Qualification Awarded: <textarea rows="3"></textarea></label>
        <div class="field-row">
          <label>Board1:
            <input type="text" name="Board1 Name">
            <label>Year of Passing Board1:
              <input type="text" name="Year of Passing Board1 ">
            </label>
            <label>Grade / Percentage Of Board1:
              <input type="text" name="Grade / Percentage Of Board1 ">
            </label>
          </label>
          <label>Board2:
            <input type="text" name="Board2 Name">
            <label>Year of Passing Board2:
              <input type="text" name="Year of Passing Board2 ">
            </label>
              <label>Grade / Percentage Of Board2:
                <input type="text" name="Grade / Percentage Of Board2 ">
              </label>
            </label>
          <label>Board3:
            <input type="text" name="Board3 Name">
            <label>Year of Passing Board3:
              <input type="text" name="Year of Passing Board3 ">
            </label>
            <label>Grade / Percentage Of Board3:
              <input type="text" name="Grade / Percentage Of Board3 ">
            </label>
          </label>
        </div>
          
        <label>Main Subjects: <textarea rows="3"></textarea></label>
        <label>Institution Name: <input type="text"></label>
        <label>Specialization: <input type="text"></label>
        <label>Additional Details: <textarea rows="3"></textarea></label>
        <label>Upload Certificate: <input type="file"></label>

        
      </fieldset>
      
      <fieldset>
        <legend>Section 4 Family Details</legend>
        <label>Spouse Name: <input type="text"></label>
        <div class="field-row">
          <label>First Child Name:
            <input type="text" name="First Child Name">
          </label>
          <label>Second Child Name:
            <input type="text" name="Second ChildName">
          </label>
        </div>
      </fieldset>
      
      <fieldset>
        <legend>Section 5 - Sibling Details</legend>
        <div class="field-row">
          <label>First Sibling Name:
            <input type="text" name="First Child Name">
            <label> Working Details: <input type="text"></label>
            <label> Designation: <input type="text"></label>
            <label> Contact Number: <input type="text"></label>
          </label>
          <label>Second Sibling Name:
            <input type="text" name="Second ChildName">
          </label>
        </div>
        <label> Working Details: <input type="text"></label>
        <label> Designation: <input type="text"></label>
        <label> Contact Number: <input type="text"></label>
      </fieldset>

      <fieldset>
        <legend>Section 6 -Passport Details</legend>
        <label> Number: <input type="text"></label>
        <label>Name On Passport: <input type="text"></label>
        <label> Place Of Issue: <input type="text"></label>
        <label>Valid Visa Details: <input type="text"></label>
        <label> Visa Validity: <input type="text"></label>
        <label> Date Of Issue: <input type="date" required></label>
        <label> Expiry Date : <input type="date" required></label>
      </fieldset>

      <div class="button-group">
        <button type="submit">Submit</button>
        <button type="reset">Reset</button>
      </div>
    </form>
  </div>
</body>
</html>
