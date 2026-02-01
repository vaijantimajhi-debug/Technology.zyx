# Technology.zyx
Oder tech projects 
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TechnologyZYX | Electronics Projects</title>
  <style>
    body{margin:0;font-family:Arial,Helvetica,sans-serif;background:#0b1c2d;color:#fff}
    header{background:linear-gradient(90deg,#0d47a1,#1976d2);padding:20px;text-align:center}
    section{padding:40px 20px;max-width:1100px;margin:auto}
    h2{color:#ffca28}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
    .card{background:#132f4c;padding:18px;border-radius:10px}
    .card h3{color:#4fc3f7;margin-top:0}
    .btn{background:#ffca28;color:#000;padding:10px 14px;border-radius:6px;text-decoration:none;font-weight:bold;display:inline-block;margin-top:8px}
    input,select,textarea{width:100%;padding:10px;margin:8px 0;border-radius:6px;border:none}
  </style>
</head>
<body>
<header>
  <h1>TechnologyZYX</h1>
  <p>Advanced Electronics & Arduino Projects (Class 8th–12th)</p>
  <p>Owner: Anurag Kumar Majhi | Providing innovative electronics projects for students and schools.</p>
</header><section>
  <h2>Order Your Project</h2>
  <form id="orderForm">
    <input id="name" placeholder="Student Name" required>
    <input id="class" placeholder="Class" required>
    <input id="school" placeholder="School Name">
    <input id="phone" placeholder="Mobile / WhatsApp" required>
    <select id="project" required>
      <option value="">Select Project</option>
      <option>1. Automatic Street Light</option>
      <option>2. Fire Alarm System</option>
      <option>3. Water Level Indicator</option>
      <option>4. Smart Dustbin</option>
      <option>5. Gas Leakage Alarm</option>
      <option>6. IR Obstacle Detector</option>
      <option>7. Temperature Monitoring System</option>
      <option>8. Rain Alarm</option>
      <option>9. Smart Door Bell</option>
      <option>10. LED Blinking (555 IC)</option>
      <option>11. Automatic Hand Sanitizer</option>
      <option>12. Smart Parking System</option>
      <option>13. Line Following Robot</option>
      <option>14. Obstacle Avoiding Robot</option>
      <option>15. Smart Fan Controller</option>
      <option>16. Light Intensity Controller</option>
      <option>17. Touch Based Switch</option>
      <option>18. Bluetooth Controlled Robot</option>
      <option>19. Voice Controlled Device</option>
      <option>20. Smart Irrigation System</option>
      <option>21. Smart Home Automation</option>
      <option>22. Automatic Night Lamp</option>
      <option>23. Digital Voting Machine</option>
      <option>24. RFID Attendance System</option>
      <option>25. Smart Blind Stick</option>
      <option>26. Earthquake Alarm</option>
      <option>27. Water Leakage Detector</option>
      <option>28. Solar Tracking System</option>
      <option>29. Smart Energy Meter</option>
      <option>30. Temperature Controlled Fan</option>
      <option>31. Motion Detector Alarm</option>
      <option>32. Visitor Counter</option>
      <option>33. Automatic Door Opener</option>
      <option>34. Smart Helmet</option>
      <option>35. Smart Attendance System</option>
      <option>36. Password Based Door Lock</option>
      <option>37. Smart Water Pump Controller</option>
      <option>38. Soil Moisture Monitoring</option>
      <option>39. Smart Street Light (Arduino)</option>
      <option>40. Bluetooth Home Automation</option>
      <option>41. Fire Fighting Robot</option>
      <option>42. Automatic Railway Gate</option>
      <option>43. Smart Gas Stove Alert</option>
      <option>44. Smart Traffic Light System</option>
      <option>45. Accident Detection System</option>
      <option>46. Smart Waste Management</option>
      <option>47. Smart Classroom System</option>
      <option>48. Smart Weather Station</option>
      <option>49. Automatic Plant Watering</option>
      <option>50. Custom Arduino Project</option>
    </select>
    <textarea id="requirement" placeholder="Custom Requirement"></textarea>
    <button type="button" class="btn" onclick="sendWhatsApp()">Order on WhatsApp</button>
  </form>
</section><footer>
  © 2026 TechnologyZYX | Owner: Anurag Kumar Majhi | Providing innovative electronics projects for students and schools.
</footer><script>
function sendWhatsApp() {
  let name = document.getElementById("name").value;
  let clas = document.getElementById("class").value;
  let school = document.getElementById("school").value;
  let phone = document.getElementById("phone").value;
  let project = document.getElementById("project").value;
  let req = document.getElementById("requirement").value;

  let message =
    "Hello, I want to order an electronics project.%0A%0A" +
    "Name: " + name + "%0A" +
    "Class: " + clas + "%0A" +
    "School: " + school + "%0A" +
    "Student Phone: " + phone + "%0A" +
    "Project: " + project + "%0A" +
    "Requirement: " + req;

  let url = "https://wa.me/918103226034?text=" + message;
  window.open(url, "_blank");
}
</script></body>
</html>
