<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Doctor Detox BMI & Plan Suggestion</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body { font-family: Arial, sans-serif; background: #f4f4f4; margin: 0; padding: 20px; }
    .container { max-width: 650px; margin: auto; background: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
    h2 { text-align: center; margin-bottom: 20px; }
    label { display: block; margin-top: 12px; font-weight: bold; }
    input, select, button { width: 100%; padding: 10px; margin-top: 6px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box; }
    select[multiple] { height: 120px; }
    .flex-row { display: flex; gap: 8px; }
    .flex-row input { flex: 1; }
    button { background: #28a745; color: #fff; border: none; cursor: pointer; font-size: 16px; }
    button.clear { background: #dc3545; margin-top: 8px; }
    button.whatsapp { background: #25D366; margin-top: 8px; }
    .result { margin-top: 20px; line-height: 1.8; font-size: 16px; }
    .highlight { color: #007bff; font-weight: bold; }
    hr { margin: 15px 0; }
    .benefit-box, .fail-box, .advantage-box { border-radius: 6px; padding: 12px; margin: 12px 0; font-size: 16px; line-height: 1.8; }
    .benefit-box { border: 1px solid #b7e4c7; background: #e9f7ef; }
    .benefit-title { background: #34c759; color: #fff; padding: 6px 10px; border-radius: 4px; font-weight: bold; margin-bottom: 6px; }
    .fail-box { border: 1px solid #f5c2c7; background: #fbeaea; }
    .fail-title { background: #dc3545; color: #fff; padding: 6px 10px; border-radius: 4px; font-weight: bold; margin-bottom: 6px; }
    .advantage-box { background: #e6f4ea; border: 1px solid #34c759; margin-top: 8px; padding: 8px; }
  </style>
</head>
<body>
<div class="container" id="formSection">
  <h2>Doctor Detox BMI & Plan Suggestion</h2>
  <label>Sales Advisor</label>
  <select id="salesAdvisor">
    <option value="">Select Advisor</option>
    <option value="+917573022404">Sales26</option>
    <option value="+917573022427">Sales27</option>
    <option value="+917573022428">Sales28</option>
    <option value="+917573022430">Sales30</option>
    <option value="+917573022431">Sales31</option>
    <option value="+917573022432">Sales32</option>
  </select>
  <label>Gender</label>
  <select id="gender" onchange="filterHealth()">
    <option value="">Select Gender</option>
    <option value="female">Female</option>
    <option value="male">Male</option>
  </select>
  <label>Full Name</label>
  <input type="text" id="name">
  <label>Mobile Number</label>
  <input type="tel" id="mobile">
  <label>Age (years)</label>
  <input type="number" id="age">
  <label>Weight (kg)</label>
  <input type="number" id="weight">
  <label>Height</label>
  <select id="heightType" onchange="toggleHeight()">
    <option value="ft" selected>Feet & Inches</option>
    <option value="cm">Centimeters</option>
  </select>
  <div id="ftInputs" class="flex-row">
    <input type="number" id="heightFt" placeholder="Feet">
    <input type="number" id="heightIn" placeholder="Inches">
  </div>
  <div id="cmInputs" style="display:none;">
    <input type="number" id="heightCm" placeholder="Centimeters">
  </div>
  <label>Health Issues (multiple)</label>
  <select id="healthIssues" multiple>
    <option>PCOD / PCOS</option>
    <option>Thyroid</option>
    <option>Diabetes</option>
    <option>Period Irregularity</option>
    <option>Menopause</option>
    <option>High BP</option>
    <option>High Cholesterol</option>
    <option>Fatty Liver</option>
    <option>Migraine</option>
    <option>Back Pain</option>
    <option>Knee Pain (Arthritis)</option>
    <option>Joint Pain</option>
    <option>Uric Acid</option>
    <option>Fibroid</option>
    <option>Gas</option>
    <option>Acidity</option>
    <option>Constipation</option>
  </select>
  <label>Tried Anything Before? (multiple)</label>
  <select id="triedBefore" multiple>
    <option>Gym/Workout</option>
    <option>Keto Diet</option>
    <option>Intermittent Fasting</option>
    <option>Herbalife/Shakes</option>
    <option>Panchakarma</option>
    <option>Naturopathy</option>
    <option>HealthifyMe/Fitelo</option>
    <option>VLCC/Slimming Center</option>
    <option>Oziva</option>
    <option>Plix</option>
    <option>Other</option>
  </select>
  <button onclick="calculate()">Calculate & Suggest</button>
  <button class="clear" onclick="resetForm()">Clear Form</button>
</div>
<div class="container" id="resultSection" style="display:none;">
  <div id="result" class="result"></div>
  <button class="whatsapp" onclick="shareWhatsApp()">📲 Share via WhatsApp</button>
  <button class="clear" onclick="newForm()">📝 Fill New Form</button>
</div>
<script>
  const sheetURL = "https://script.google.com/macros/s/AKfycby2xfglNxCKX2mFhjiQ8mtDnLkOTsSWAtdlpoyiiQJag30U9UjEFvVErfvNgJ4EYz_f/exec";
  
  const idealMap = {
    "4-5": { male: [35, 39], female: [33, 37] }, "4-6": { male: [37, 41], female: [35, 39] },
    "4-7": { male: [39, 43], female: [37, 41] }, "4-8": { male: [41, 45], female: [39, 43] },
    "4-9": { male: [43, 47], female: [41, 45] }, "4-10": { male: [45, 49], female: [43, 47] },
    "4-11": { male: [47, 51], female: [45, 49] }, "5-0": { male: [50, 54], female: [48, 50] },
    "5-1": { male: [52, 56], female: [50, 52] }, "5-2": { male: [54, 58], female: [52, 54] },
    "5-3": { male: [56, 60], female: [54, 56] }, "5-4": { male: [58, 62], female: [56, 58] },
    "5-5": { male: [60, 64], female: [58, 60] }, "5-6": { male: [62, 66], female: [60, 62] },
    "5-7": { male: [64, 68], female: [62, 64] }, "5-8": { male: [66, 70], female: [64, 66] },
    "5-9": { male: [68, 72], female: [66, 68] }, "5-10": { male: [70, 74], female: [68, 70] },
    "5-11": { male: [72, 76], female: [70, 72] }, "6-0": { male: [74, 78], female: [72, 74] },
    "6-1": { male: [76, 80], female: [74, 76] }, "6-2": { male: [78, 82], female: [76, 78] },
    "6-3": { male: [80, 84], female: [78, 80] }, "6-4": { male: [82, 86], female: [80, 82] }
  };

  const benefitsMap = {
    "PCOD / PCOS": "🩺 PCOD/PCOS\nHormonal imbalance weight badhata hai. Detox hormones balance karta hai, periods regular hoti hain, acne reduce hota hai.\n✅ Clients ne PCOD medicines kam ki hain.",
    "Thyroid": "🦋 Thyroid\nMetabolism slow hota hai, weight easily badhta hai. Detox metabolism fast karta hai, hormones balance hota hai.\n✅ Thyroid patients ne positive results dekhe.",
    "Diabetes": "🍬 Diabetes\nInsulin resistance badhta hai. Detox weight loss karta hai, sugar control hota hai.\n✅ Clients ne sugar medicines kam/band ki hain.",
    "High BP": "🩺 Blood Pressure\nWeight badhne se BP badhta hai. Detox se BP naturally control hota hai.\n✅ Clients ne BP medicines reduce ki.",
    "High Cholesterol": "🩺 Cholesterol\nWeight gain cholesterol badhata hai. Detox cholesterol control karta hai aur heart risk reduce hota hai.",
    "Fatty Liver": "🍖 Fatty Liver\nLiver me fat deposit hota hai. Detox liver fat reduce karta hai, liver healthy banata hai.",
    "Migraine": "🤕 Migraine\nLiver imbalance migraine trigger karta hai. Detox liver function improve karke relief deta hai.",
    "Back Pain": "🦵 Back Pain\nWeight badhne se spine load badhta hai. Detox weight kam karke pain reduce karta hai.",
    "Knee Pain (Arthritis)": "🦵 Knee Pain\nOverweight knees par load badhata hai. Detox weight kam karke relief deta hai.",
    "Joint Pain": "🦶 Joint Pain\nWeight gain joints par stress dalta hai. Detox se swelling kam hoti hai.",
    "Uric Acid": "💧 Uric Acid\nWeight gain uric acid badhata hai. Detox uric acid control karta hai.",
    "Fibroid": "🎀 Fibroid\nHormonal imbalance fibroid ko badhata hai. Detox hormones balance karke relief deta hai.",
    "Gas": "💨 Gas\nDetox digestion improve karke bloating reduce karta hai.",
    "Acidity": "🔥 Acidity\nDetox acid neutral karke acidity control karta hai.",
    "Constipation": "🚽 Constipation\nDetox gut health improve karke bowel regulate karta hai."
  };

  const failMap = {
    "Gym/Workout": "🚫 Gym\nSlow results—months lagte hain 1 month ka result ke liye.\nCostly trainers, memberships, injury risk.\n✅ Detox Advantage: Lose up to 7–8 kg weight-loss naturally.",
    "Keto Diet": "🚫 Keto\nHigh fat & protein cholesterol badhata hai.\nDifficult diet, rebound weight.\n✅ Detox Advantage: Balanced Ayurvedic fat loss.",
    "Intermittent Fasting": "🚫 Fasting\nTemporary maintenance, weakness, rebound.\n✅ Detox Advantage: Metabolism reset permanent loss.",
    "Herbalife/Shakes": "🚫 Herbalife\nPowder shakes harm liver/kidney.\nRebound weight.\n✅ Detox Advantage: Real food, herbs permanent loss.",
    "Panchakarma": "🚫 Panchakarma\nClinic visits costly, time-consuming.\n✅ Detox Advantage: Home-based weight loss.",
    "Naturopathy": "🚫 Naturopathy\nStay-in centers costly, rebound after.\n✅ Detox Advantage: Home-based, lasting results.",
    "HealthifyMe/Fitelo": "🚫 Apps\nCalorie count focus, slow results.\n✅ Detox Advantage: Expert metabolism fix.",
    "VLCC/Slimming Center": "🚫 VLCC\nMachines costly, temporary.\n✅ Detox Advantage: Liver detox fast results.",
    "Oziva": "🚫 Oziva\nSupplements no root cause fix.\n✅ Detox Advantage: Ayurvedic detox real food.",
    "Plix": "🚫 Plix\nPowders minimal loss.\n✅ Detox Advantage: Natural fat loss.",
    "Other": "✅ Detox Advantage\nAyurvedic detox + support."
  };

  function filterHealth() {
    const g = document.getElementById('gender').value;
    document.querySelectorAll('#healthIssues option').forEach(o => {
      if (["PCOD / PCOS", "Period Irregularity", "Menopause", "Fibroid"].includes(o.value)) {
        o.style.display = g === 'female' ? 'block' : 'none';
        if (g !== 'female') o.selected = false;
      }
    });
  }

  function toggleHeight() {
    const t = document.getElementById('heightType').value;
    document.getElementById('ftInputs').style.display = t === 'ft' ? 'flex' : 'none';
    document.getElementById('cmInputs').style.display = t === 'cm' ? 'block' : 'none';
  }

  function resetForm() {
    document.querySelectorAll('#formSection input, #formSection select').forEach(e => e.value = '');
    document.getElementById('resultSection').style.display = 'none';
    document.getElementById('formSection').style.display = 'block';
  }

  let report = {};

  function calculate() {
    const gender = document.getElementById('gender').value;
    const name = document.getElementById('name').value.trim();
    const mobile = document.getElementById('mobile').value.trim();
    const age = +document.getElementById('age').value;
    const weight = +document.getElementById('weight').value;
    const health = Array.from(document.getElementById('healthIssues').selectedOptions).map(o => o.value);
    const tried = Array.from(document.getElementById('triedBefore').selectedOptions).map(o => o.value);
    
    let ft = 0, inch = 0, heightCm = 0;

    if (document.getElementById('heightType').value === 'cm') {
      heightCm = +document.getElementById('heightCm').value;
      ft = Math.floor(heightCm / 30.48); 
      inch = Math.round((heightCm / 2.54) % 12);
    } else {
      ft = +document.getElementById('heightFt').value || 0;
      inch = +document.getElementById('heightIn').value || 0;
      heightCm = (ft * 12 + inch) * 2.54;
    }

    if (!gender || !name || !mobile || !age || !weight || heightCm <= 0) { alert('Please fill all fields!'); return; }

    const bmi = +(weight / ((heightCm / 100) ** 2)).toFixed(2);
    const category = bmi < 18.5 ? 'Underweight' : bmi <= 24.9 ? 'Normal' : bmi <= 29.9 ? 'Overweight' : 'Obese';
    const key = `${ft}-${inch}`;

    if (!idealMap[key]) { alert("Height not found!"); return; }

    const [minW, maxW] = idealMap[key][gender];
    let toLose = 0, months = 0, program = '';

    if (weight > maxW) {
      toLose = +(weight - maxW).toFixed(1);
      months = Math.ceil(toLose / 7.5);
      program = `${months} Detox + ${months} Maintenance (${months} months)`;
    } else {
      program = '1-Month Detox & Maintenance';
    }

    const benefitsHTML = health.map(h => `<div class="benefit-box"><div class="benefit-title">${benefitsMap[h].split("\n")[0]}</div>${benefitsMap[h].split("\n").slice(1).join("<br>")}</div>`).join('');
    const failHTML = tried.map(m => `<div class="fail-box"><div class="fail-title">${failMap[m].split("\n")[0]}</div>${failMap[m].split("\n").slice(1, -1).join("<br>")}<div class="advantage-box">${failMap[m].split("\n").slice(-1)}</div></div>`).join('');

    document.getElementById('result').innerHTML = `
      <p><b>Name:</b> ${name}</p>
      <p><b>Mobile:</b> ${mobile}</p>
      <p><b>Age:</b> ${age} yrs | <b>Gender:</b> ${gender}</p>
      <hr>
      <p>📊 <b>BMI:</b> <span class="highlight">${bmi}</span> (${category})</p>
      <p>✅ <b>Ideal Weight Range:</b> <span class="highlight">${minW} – ${maxW} kg</span></p>
      ${toLose > 0 ? `<p>⏳ <b>Timeline:</b> ${months} months (up to 7–8 kg weight-loss/month)</p>` : ''}
      <p>💡 <b>Suggested Program:</b> ${program}</p>
      ${benefitsHTML ? `<hr><b>Benefits for Your Health Issues:</b>${benefitsHTML}` : ''}
      ${failHTML ? `<hr><b>Why Previous Methods Didn't Work:</b>${failHTML}` : ''}
      <hr><b>What We Provide:</b><br>
      ✔ 100% Ayurvedic Liver Detox<br>
      ✔ Daily Client Manager Support<br>
      ✔ up to 7–8 kg weight-loss/month Naturally<br>
      ✔ Real Food Diet (No Fasting / No Exercise)
    `;

    fetch(sheetURL, {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({
        name, mobile, age, gender, weight,
        height: `${ft}'${inch}"`,
        bmi,
        idealRange: `${minW}-${maxW}`,
        timeline: `${months || 1} months`,
        program,
        health: health.join(", "),
        triedBefore: tried.join(", ")
      })
    })
    .then(response => {
      if (response.ok) {
        console.log("✅ Google Sheets updated successfully.");
      } else {
        console.error("❌ Google Sheets update failed:", response.status);
      }
    })
    .catch(err => console.error("❌ Error sending to Google Sheets:", err));

    const benefitsMsg = health.map(h => benefitsMap[h]).join("\n\n");
    const failMsg = tried.map(m => failMap[m]).join("\n\n");
    
    report = { number: mobile.replace(/\s+/g, ''), msg: encodeURIComponent(
      `Hello ${name}, here’s your Doctor Detox BMI Report:
      📊 BMI: ${bmi} (${category})
      ✅ Ideal Weight: ${minW} – ${maxW} kg
      ⏳ Timeline: ${months || 1} months (up to 7–8 kg weight-loss/month)
      💡 Suggested Program: ${program}
      🔥 Benefits for Your Health Issues:
      ${benefitsMsg}
      🚫 Why Previous Methods Didn't Work:
      ${failMsg}
      ✨ What We Provide:
      ✔ 100% Ayurvedic Liver Detox
      ✔ Daily Client Manager Support
      ✔ up to 7–8 kg weight-loss/month
      ✔ Real Food Diet (No Fasting / No Exercise)`
    )};

    document.getElementById('formSection').style.display = 'none';
    document.getElementById('resultSection').style.display = 'block';
    window.scrollTo({ top: document.getElementById('resultSection').offsetTop, behavior: 'smooth' });
  }

  function newForm() { resetForm(); }
  function shareWhatsApp() { window.open(`https://wa.me/${report.number}?text=${report.msg}`, '_blank'); }
</script>
</body>
</html>
