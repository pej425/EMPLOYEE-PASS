<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Pass Requisition Form</title>
</head>
<body>
    <h2>Employee Pass Requisition Form</h2>
    
    <form action="https://formspree.io/f/your-email" method="POST">
        <label for="company">Name of Company:</label>
        <input type="text" id="company" name="company" required><br><br>

        <label for="emp_name">Employee Name:</label>
        <input type="text" id="emp_name" name="emp_name" required><br><br>

        <label for="emp_no">Employee No.:</label>
        <input type="text" id="emp_no" name="emp_no" required><br><br>

        <label for="designation">Designation:</label>
        <input type="text" id="designation" name="designation" required><br><br>

        <label for="nric">NRIC No.:</label>
        <input type="text" id="nric" name="nric" required><br><br>

        <label for="department">Department:</label>
        <input type="text" id="department" name="department" required><br><br>

        <label for="description">Description:</label>
        <select id="description" name="description" required>
            <option value="newly_joined">Newly Joined - NIL</option>
            <option value="1st_replacement">1st Replacement - RM5.00</option>
            <option value="2nd_replacement">2nd Replacement - RM10.00</option>
            <option value="damage">Damage (Specify Below)</option>
        </select><br><br>

        <label for="damage_reason">Reason (If damaged):</label>
        <input type="text" id="damage_reason" name="damage_reason"><br><br>

        <label for="amount_received">Amount Received:</label>
        <input type="text" id="amount_received" name="amount_received"><br><br>

        <label for="date_received">Date Received:</label>
        <input type="date" id="date_received" name="date_received"><br><br>

        <label for="received_by">Received By:</label>
        <input type="text" id="received_by" name="received_by"><br><br>

        <label for="signature">Employee Signature:</label>
        <input type="text" id="signature" name="signature"><br><br>

        <button type="submit">Submit</button>
    </form>
</body>
</html>
