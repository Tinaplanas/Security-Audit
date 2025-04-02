<h1>📋 Controls and Compliance Assessment</h1>

<h2>🧪 Case Study</h2>

<p><b>Botium Toys</b> is a small U.S. business that develops and sells toys. It operates from a single physical location that houses their main office, storefront, and warehouse. However, their online presence has expanded rapidly — reaching international customers and increasing pressure on their IT department.</p>

<p>The IT manager is concerned about lacking a solid plan for business continuity and compliance as the company scales. She initiates an internal audit using the <b>NIST Cybersecurity Framework (CSF)</b> to secure infrastructure and identify gaps related to compliance, risk, and critical asset protection.</p>

<p><b>🎯 Audit Goal:</b> Assess current risks and evaluate the company’s security posture, including potential legal or financial consequences due to non-compliance.</p>

<hr>

<h2>📂 Scenario Overview</h2>

<h3>🧭 Scope</h3>
The audit covers the entire Botium Toys security program — including IT assets, policies, procedures, and implementation of best practices across technical, physical, and administrative areas.

<h3>🎯 Goals</h3>
<ul>
  <li>Evaluate existing IT assets</li>
  <li>Complete a compliance checklist</li>
  <li>Identify areas for control improvements</li>
</ul>

<h3>💻 Current Assets</h3>
<ul>
  <li>On-premises business equipment</li>
  <li>Employee devices: laptops, phones, peripherals, headsets, etc.</li>
  <li>Storefront retail systems and inventory storage</li>
  <li>Software/systems: accounting, databases, security, eCommerce</li>
  <li>Internal network & internet access</li>
  <li>Data storage and retention infrastructure</li>
  <li>Legacy systems requiring manual support</li>
</ul>

<hr>

<h2>⚠️ Risk Assessment</h2>

<h3>📉 Risk Description</h3>
<p>Asset management is inconsistent, and essential controls are missing. Botium Toys may not comply with U.S. or international standards like PCI DSS or GDPR.</p>

<h3>✅ Control Best Practices</h3>
<p>Using the Identify function from NIST CSF, the IT team must inventory and classify assets to evaluate their importance to business continuity.</p>

<h3>📊 Risk Score</h3>
<p><b>8 out of 10</b> — High risk due to lack of controls and poor compliance posture.</p>

<h3>🗒️ Additional Comments</h3>
<ul>
  <li>Impact of asset loss is rated <b>medium</b> due to lack of visibility.</li>
  <li>Risk of non-compliance fines is <b>high</b>.</li>
  <li>Controls must be implemented to protect critical data and meet regulatory obligations.</li>
</ul>

<h3>🔐 Control Types</h3>
<ul>
  <li><b>Administrative</b>: Policies, training, procedures</li>
  <li><b>Technical</b>: Firewalls, antivirus, encryption</li>
  <li><b>Physical</b>: Locks, surveillance, access restrictions</li>
</ul>

<h3>🛡️ Security Control Categories</h3>
<ul>
  <li>🛑 <b>Preventative</b>: Stop incidents from occurring</li>
  <li>🕵️‍♀️ <b>Detective</b>: Identify active or past threats</li>
  <li>🛠️ <b>Corrective</b>: Restore functionality after an incident</li>
  <li>🚫 <b>Deterrent</b>: Discourage malicious actions</li>
</ul>

<hr>

<h2>✅ Controls Assessment Checklist</h2>

<table>
  <tr><th>Yes / No / ?</th><th>Control</th><th>Explanation</th></tr>
  <tr><td>No</td><td>Least Privilege</td><td>Employees have access to customer data. This access must be restricted.</td></tr>
  <tr><td>No</td><td>Disaster Recovery Plan</td><td>No plan currently exists. This is essential for continuity.</td></tr>
  <tr><td>Yes</td><td>Firewall</td><td>Firewall is in place with defined security rules.</td></tr>
  <tr><td>?</td><td>Password Policies</td><td>A weak policy exists, undermining access control.</td></tr>
  <tr><td>Yes</td><td>Antivirus</td><td>IT monitors antivirus software regularly.</td></tr>
  <tr><td>No</td><td>Backups</td><td>No backup plan exists. Strategies like full/incremental backups are needed.</td></tr>
  <tr><td>No</td><td>Encryption</td><td>Encryption is needed to protect data confidentiality.</td></tr>
  <tr><td>No</td><td>IDS</td><td>Intrusion Detection Systems are not yet implemented.</td></tr>
  <tr><td>Yes</td><td>Storefront</td><td>Physical controls like locks are present at the store.</td></tr>
  <tr><td>Yes</td><td>CCTV</td><td>Surveillance system is operational.</td></tr>
  <tr><td>Yes</td><td>Fire Detection</td><td>Systems are installed; a maintenance plan is needed.</td></tr>
</table>

<hr>

<h2>📜 Compliance Checklist</h2>

<h3>💳 PCI DSS</h3>

<table>
  <tr><th>Yes / No / ?</th><th>Best Practice</th><th>Explanation</th></tr>
  <tr><td>No</td><td>Restrict credit card access</td><td>All employees currently have access — this must be limited.</td></tr>
  <tr><td>No</td><td>Secure storage</td><td>Credit card info is unencrypted — a clear violation.</td></tr>
  <tr><td>No</td><td>Encryption</td><td>Encryption has not yet been implemented.</td></tr>
</table>

<h3>🇪🇺 GDPR</h3>

<table>
  <tr><th>Yes / No / ?</th><th>Best Practice</th><th>Explanation</th></tr>
  <tr><td>No</td><td>Secure EU customer data</td><td>GDPR standards are not followed — risking EU penalties.</td></tr>
  <tr><td>Yes</td><td>Privacy policies</td><td>Privacy policies are actively maintained.</td></tr>
</table>

<h3>📊 SOC Controls</h3>

<table>
  <tr><th>Yes / No / ?</th><th>Best Practice</th><th>Explanation</th></tr>
  <tr><td>No</td><td>User access policies</td><td>Employees can access all internal data.</td></tr>
  <tr><td>Yes</td><td>Data integrity</td><td>Data is consistent and accurate.</td></tr>
  <tr><td>No</td><td>Access control</td><td>Access isn’t limited to authorized users only.</td></tr>
</table>

<hr>

<h2>📌 Recommendations</h2>

<p>Botium Toys’ current security posture lacks sufficient protection for sensitive data. Key areas for improvement include:</p>

<ol>
  <li>Implementing least privilege access</li>
  <li>Creating a formal disaster recovery plan</li>
  <li>Strengthening password policies and MFA</li>
  <li>Encrypting all sensitive customer and financial data</li>
  <li>Deploying a password management system</li>
</ol>

<p>To meet compliance standards and reduce risk, Botium Toys must formalize IT governance processes and adopt industry best practices. Regular audits and updated asset inventories will ensure proactive security moving forward.</p>

<hr>
