
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Stock Management CRM</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        :root {
            --primary: #2563eb;
            --primary-dark: #1d4ed8;
            --danger: #dc2626;
            --success: #16a34a;
            --warning: #ca8a04;
            --bg: #f1f5f9;
            --card: #ffffff;
            --text: #1e293b;
            --text-light: #64748b;
            --border: #e2e8f0;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: var(--bg);
            color: var(--text);
            min-height: 100vh;
            padding-bottom: 80px;
        }
        .container { max-width: 800px; margin: 0 auto; padding: 16px; }
        
        /* Header */
        .header {
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            color: white;
            padding: 24px 16px;
            text-align: center;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
        }
        .header h1 { font-size: 1.5rem; font-weight: 700; }
        .header p { opacity: 0.9; margin-top: 4px; font-size: 0.9rem; }

        /* Navigation */
        .nav {
            display: flex;
            gap: 8px;
            padding: 12px 16px;
            background: var(--card);
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
            overflow-x: auto;
            -webkit-overflow-scrolling: touch;
        }
        .nav-btn {
            flex: 1;
            min-width: 100px;
            padding: 10px 16px;
            border: 2px solid var(--border);
            background: var(--card);
            border-radius: 10px;
            font-size: 0.85rem;
            font-weight: 600;
            color: var(--text-light);
            cursor: pointer;
            transition: all 0.2s;
            white-space: nowrap;
        }
        .nav-btn.active {
            background: var(--primary);
            color: white;
            border-color: var(--primary);
        }
        .nav-btn:active { transform: scale(0.96); }

        /* Cards */
        .card {
            background: var(--card);
            border-radius: 16px;
            padding: 20px;
            margin-bottom: 16px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.05);
        }
        .card-title {
            font-size: 1.1rem;
            font-weight: 700;
            margin-bottom: 16px;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        .card-title .icon { font-size: 1.3rem; }

        /* Forms */
        .form-group { margin-bottom: 16px; }
        .form-label {
            display: block;
            font-size: 0.85rem;
            font-weight: 600;
            color: var(--text-light);
            margin-bottom: 6px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        .form-input {
            width: 100%;
            padding: 12px 16px;
            border: 2px solid var(--border);
            border-radius: 10px;
            font-size: 1rem;
            transition: border-color 0.2s;
            -webkit-appearance: none;
        }
        .form-input:focus {
            outline: none;
            border-color: var(--primary);
        }
        .btn {
            width: 100%;
            padding: 14px;
            border: none;
            border-radius: 10px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.2s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }
        .btn-primary {
            background: var(--primary);
            color: white;
        }
        .btn-primary:active { background: var(--primary-dark); }
        .btn-success { background: var(--success); color: white; }
        .btn-danger { background: var(--danger); color: white; }
        .btn-warning { background: var(--warning); color: white; }
        .btn-secondary {
            background: var(--bg);
            color: var(--text);
            border: 2px solid var(--border);
        }
        .btn:active { transform: scale(0.98); }

        /* Scanner */
        .scanner-container {
            position: relative;
            width: 100%;
            height: 300px;
            background: #000;
            border-radius: 16px;
            overflow: hidden;
            margin-bottom: 16px;
        }
        #scanner-video {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .scanner-overlay {
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: rgba(0,0,0,0.3);
        }
        .scanner-frame {
            width: 280px;
            height: 100px;
            border: 3px solid var(--success);
            border-radius: 12px;
            position: relative;
        }
        .scanner-frame::before, .scanner-frame::after {
            content: '';
            position: absolute;
            width: 20px; height: 20px;
            border-color: var(--success);
            border-style: solid;
        }
        .scanner-frame::before { top: -3px; left: -3px; border-width: 3px 0 0 3px; }
        .scanner-frame::after { bottom: -3px; right: -3px; border-width: 0 3px 3px 0; }
        .scanner-laser {
            position: absolute;
            top: 0; left: 0; right: 0;
            height: 2px;
            background: #ef4444;
            box-shadow: 0 0 8px #ef4444;
            animation: scan 2s linear infinite;
        }
        @keyframes scan {
            0% { top: 0; opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { top: 100%; opacity: 0; }
        }
        .scanner-status {
            color: white;
            margin-top: 16px;
            font-size: 0.9rem;
            text-shadow: 0 1px 2px rgba(0,0,0,0.5);
        }

        /* Lists */
        .list { display: flex; flex-direction: column; gap: 12px; }
        .list-item {
            background: var(--bg);
            border-radius: 12px;
            padding: 16px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: transform 0.2s;
        }
        .list-item:active { transform: scale(0.99); }
        .list-item-info { flex: 1; }
        .list-item-title { font-weight: 700; font-size: 1rem; }
        .list-item-sub {
            font-size: 0.85rem;
            color: var(--text-light);
            margin-top: 4px;
        }
        .list-item-badge {
            background: var(--primary);
            color: white;
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 0.75rem;
            font-weight: 700;
        }
        .list-item-actions {
            display: flex;
            gap: 8px;
            margin-left: 12px;
        }
        .icon-btn {
            width: 36px; height: 36px;
            border-radius: 8px;
            border: none;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            font-size: 1rem;
        }
        .icon-btn-edit { background: #dbeafe; color: var(--primary); }
        .icon-btn-delete { background: #fee2e2; color: var(--danger); }
        .icon-btn-transfer { background: #fef3c7; color: var(--warning); }

        /* Search */
        .search-box {
            position: relative;
            margin-bottom: 16px;
        }
        .search-box .form-input { padding-left: 44px; }
        .search-icon {
            position: absolute;
            left: 16px;
            top: 50%;
            transform: translateY(-50%);
            color: var(--text-light);
            font-size: 1.1rem;
        }

        /* Stats */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 12px;
            margin-bottom: 16px;
        }
        .stat-card {
            background: var(--card);
            border-radius: 12px;
            padding: 16px;
            text-align: center;
            box-shadow: 0 1px 3px rgba(0,0,0,0.05);
        }
        .stat-value {
            font-size: 1.8rem;
            font-weight: 800;
            color: var(--primary);
        }
        .stat-label {
            font-size: 0.8rem;
            color: var(--text-light);
            margin-top: 4px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        /* Modal */
        .modal-overlay {
            position: fixed;
            top: 0; left: 0; right: 0; bottom: 0;
            background: rgba(0,0,0,0.5);
            display: none;
            align-items: flex-end;
            justify-content: center;
            z-index: 1000;
            backdrop-filter: blur(4px);
        }
        .modal-overlay.active { display: flex; }
        .modal {
            background: var(--card);
            width: 100%;
            max-width: 500px;
            max-height: 90vh;
            border-radius: 24px 24px 0 0;
            padding: 24px;
            overflow-y: auto;
            animation: slideUp 0.3s ease;
        }
        @keyframes slideUp {
            from { transform: translateY(100%); }
            to { transform: translateY(0); }
        }
        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        .modal-title { font-size: 1.2rem; font-weight: 700; }
        .modal-close {
            width: 36px; height: 36px;
            border-radius: 50%;
            border: none;
            background: var(--bg);
            font-size: 1.2rem;
            cursor: pointer;
        }

        /* Phone Serials View */
        .serials-list {
            display: flex;
            flex-direction: column;
            gap: 8px;
        }
        .serial-item {
            background: var(--bg);
            padding: 12px 16px;
            border-radius: 10px;
            font-family: 'Courier New', monospace;
            font-size: 0.9rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .serial-item .date {
            font-size: 0.75rem;
            color: var(--text-light);
            font-family: sans-serif;
        }

        /* Empty State */
        .empty-state {
            text-align: center;
            padding: 40px 20px;
            color: var(--text-light);
        }
        .empty-state .icon { font-size: 3rem; margin-bottom: 12px; opacity: 0.5; }
        .empty-state h3 { font-size: 1.1rem; margin-bottom: 8px; }

        /* Select */
        select.form-input {
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='%2364748b' stroke-width='2'%3E%3Cpolyline points='6 9 12 15 18 9'%3E%3C/polyline%3E%3C/svg%3E");
            background-repeat: no-repeat;
            background-position: right 12px center;
            background-size: 20px;
            padding-right: 40px;
            appearance: none;
        }

        /* Toast */
        .toast {
            position: fixed;
            bottom: 100px;
            left: 50%;
            transform: translateX(-50%) translateY(100px);
            background: var(--text);
            color: white;
            padding: 12px 24px;
            border-radius: 10px;
            font-size: 0.9rem;
            z-index: 2000;
            opacity: 0;
            transition: all 0.3s;
            white-space: nowrap;
        }
        .toast.show {
            opacity: 1;
            transform: translateX(-50%) translateY(0);
        }

        /* Hide sections */
        .section { display: none; }
        .section.active { display: block; }

        /* Responsive */
        @media (max-width: 400px) {
            .stats-grid { grid-template-columns: 1fr; }
            .scanner-frame { width: 240px; }
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>📱 Stock Management CRM</h1>
        <p>Manage employees & phone inventory</p>
    </div>

    <nav class="nav">
        <button class="nav-btn active" onclick="showSection('dashboard')">📊 Dashboard</button>
        <button class="nav-btn" onclick="showSection('employees')">👥 Agents</button>
        <button class="nav-btn" onclick="showSection('stock')">📦 Stock</button>
        <button class="nav-btn" onclick="showSection('transfer')">🔄 Transfer</button>
    </nav>

    <div class="container">

        <!-- DASHBOARD -->
        <div id="dashboard" class="section active">
            <div class="stats-grid">
                <div class="stat-card">
                    <div class="stat-value" id="stat-agents">0</div>
                    <div class="stat-label">Total Agents</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value" id="stat-phones">0</div>
                    <div class="stat-label">Total Phones</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value" id="stat-instock">0</div>
                    <div class="stat-label">In Stock</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value" id="stat-allocated">0</div>
                    <div class="stat-label">Allocated</div>
                </div>
            </div>

            <div class="card">
                <div class="card-title"><span class="icon">🔍</span> Quick Search</div>
                <div class="search-box">
                    <span class="search-icon">🔎</span>
                    <input type="text" class="form-input" id="quick-search" placeholder="Search agents by name or phone..." oninput="quickSearch(this.value)">
                </div>
                <div id="quick-search-results"></div>
            </div>

            <div class="card">
                <div class="card-title"><span class="icon">📋</span> Recent Activity</div>
                <div id="recent-activity" class="list"></div>
            </div>
        </div>

        <!-- EMPLOYEES -->
        <div id="employees" class="section">
            <div class="card">
                <div class="card-title"><span class="icon">➕</span> Add New Agent</div>
                <form onsubmit="addEmployee(event)">
                    <div class="form-group">
                        <label class="form-label">Full Name</label>
                        <input type="text" class="form-input" id="emp-name" placeholder="e.g. John Doe" required>
                    </div>
                    <div class="form-group">
                        <label class="form-label">Phone Number</label>
                        <input type="tel" class="form-input" id="emp-phone" placeholder="e.g. +254 712 345 678" required>
                    </div>
                    <button type="submit" class="btn btn-primary">👤 Add Agent</button>
                </form>
            </div>

            <div class="card">
                <div class="card-title"><span class="icon">👥</span> All Agents</div>
                <div class="search-box">
                    <span class="search-icon">🔎</span>
                    <input type="text" class="form-input" placeholder="Search agents..." oninput="searchEmployees(this.value)">
                </div>
                <div id="employees-list" class="list"></div>
            </div>
        </div>

        <!-- STOCK -->
        <div id="stock" class="section">
            <div class="card">
                <div class="card-title"><span class="icon">📷</span> Scan IMEI Barcode</div>
                <div class="scanner-container" id="scanner-box" style="display:none;">
                    <video id="scanner-video" autoplay playsinline muted></video>
                    <div class="scanner-overlay">
                        <div class="scanner-frame">
                            <div class="scanner-laser"></div>
                        </div>
                        <div class="scanner-status">Align barcode within frame</div>
                    </div>
                </div>
                <div id="scanner-fallback" style="display:none;">
                    <p style="color: var(--text-light); margin-bottom: 12px; text-align: center;">Camera not available. Enter IMEI manually:</p>
                </div>
                <button class="btn btn-secondary" id="scan-btn" onclick="toggleScanner()">📷 Start Camera Scan</button>
                
                <form onsubmit="allocateStock(event)" style="margin-top: 16px;">
                    <div class="form-group">
                        <label class="form-label">IMEI / Serial Number</label>
                        <input type="text" class="form-input" id="stock-imei" placeholder="Scan or type IMEI..." required>
                    </div>
                    <div class="form-group">
                        <label class="form-label">Phone Model (Optional)</label>
                        <input type="text" class="form-input" id="stock-model" placeholder="e.g. iPhone 15 Pro">
                    </div>
                    <div class="form-group">
                        <label class="form-label">Allocate To Agent</label>
                        <select class="form-input" id="stock-agent" required>
                            <option value="">Select Agent...</option>
                        </select>
                    </div>
                    <button type="submit" class="btn btn-success">📦 Allocate Stock</button>
                </form>
            </div>

            <div class="card">
                <div class="card-title"><span class="icon">📋</span> All Stock</div>
                <div class="search-box">
                    <span class="search-icon">🔎</span>
                    <input type="text" class="form-input" placeholder="Search by IMEI or model..." oninput="searchStock(this.value)">
                </div>
                <div id="stock-list" class="list"></div>
            </div>
        </div>

        <!-- TRANSFER -->
        <div id="transfer" class="section">
            <div class="card">
                <div class="card-title"><span class="icon">🔄</span> Transfer Stock Between Agents</div>
                <form onsubmit="transferStock(event)">
                    <div class="form-group">
                        <label class="form-label">From Agent</label>
                        <select class="form-input" id="transfer-from" onchange="loadTransferStock()" required>
                            <option value="">Select Source Agent...</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label class="form-label">Select Phone (IMEI)</label>
                        <select class="form-input" id="transfer-phone" required>
                            <option value="">Select Phone...</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label class="form-label">To Agent</label>
                        <select class="form-input" id="transfer-to" required>
                            <option value="">Select Destination Agent...</option>
                        </select>
                    </div>
                    <button type="submit" class="btn btn-warning">🔄 Confirm Transfer</button>
                </form>
            </div>

            <div class="card">
                <div class="card-title"><span class="icon">📜</span> Transfer History</div>
                <div id="transfer-history" class="list"></div>
            </div>
        </div>

    </div>

    <!-- Modal for viewing agent phones -->
    <div class="modal-overlay" id="agent-modal">
        <div class="modal">
            <div class="modal-header">
                <div class="modal-title" id="modal-title">Agent Phones</div>
                <button class="modal-close" onclick="closeModal()">✕</button>
            </div>
            <div id="modal-content"></div>
        </div>
    </div>

    <div class="toast" id="toast"></div>

    <script>
        // ==================== DATA STORE ====================
        const DB = {
            get(key) {
                const data = localStorage.getItem('crm_' + key);
                return data ? JSON.parse(data) : [];
            },
            set(key, value) {
                localStorage.setItem('crm_' + key, JSON.stringify(value));
            }
        };

        // ==================== STATE ====================
        let scannerActive = false;
        let scannerStream = null;
        let barcodeDetector = null;

        // ==================== INIT ====================
        document.addEventListener('DOMContentLoaded', () => {
            initBarcodeDetector();
            updateStats();
            renderEmployees();
            renderStock();
            renderTransferHistory();
            populateAgentSelects();
            renderRecentActivity();
        });

        // ==================== NAVIGATION ====================
        function showSection(id) {
            document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
            document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
            document.getElementById(id).classList.add('active');
            event.target.classList.add('active');
            
            if (id === 'employees') renderEmployees();
            if (id === 'stock') { renderStock(); populateAgentSelects(); }
            if (id === 'transfer') populateTransferSelects();
            if (id === 'dashboard') { updateStats(); renderRecentActivity(); }
        }

        // ==================== TOAST ====================
        function showToast(msg) {
            const t = document.getElementById('toast');
            t.textContent = msg;
            t.classList.add('show');
            setTimeout(() => t.classList.remove('show'), 2500);
        }

        // ==================== BARCODE SCANNER ====================
        async function initBarcodeDetector() {
            if ('BarcodeDetector' in window) {
                try {
                    barcodeDetector = new BarcodeDetector({ formats: ['code_128', 'code_39', 'ean_13', 'ean_8', 'upc_a', 'upc_e', 'qr_code'] });
                } catch (e) {
                    console.log('BarcodeDetector init failed:', e);
                }
            }
            if (!barcodeDetector) {
                document.getElementById('scanner-fallback').style.display = 'block';
                document.getElementById('scan-btn').style.display = 'none';
            }
        }

        async function toggleScanner() {
            const box = document.getElementById('scanner-box');
            const btn = document.getElementById('scan-btn');
            
            if (scannerActive) {
                stopScanner();
                box.style.display = 'none';
                btn.textContent = '📷 Start Camera Scan';
                scannerActive = false;
            } else {
                try {
                    const stream = await navigator.mediaDevices.getUserMedia({ 
                        video: { facingMode: 'environment', width: { ideal: 1280 }, height: { ideal: 720 } }
                    });
                    scannerStream = stream;
                    const video = document.getElementById('scanner-video');
                    video.srcObject = stream;
                    await video.play();
                    
                    box.style.display = 'block';
                    btn.textContent = '⏹ Stop Scanner';
                    scannerActive = true;
                    
                    scanLoop();
                } catch (err) {
                    showToast('Camera access denied or unavailable');
                    document.getElementById('scanner-fallback').style.display = 'block';
                }
            }
        }

        function stopScanner() {
            if (scannerStream) {
                scannerStream.getTracks().forEach(t => t.stop());
                scannerStream = null;
            }
        }

        async function scanLoop() {
            if (!scannerActive || !barcodeDetector) return;
            
            const video = document.getElementById('scanner-video');
            if (video.readyState === video.HAVE_ENOUGH_DATA) {
                try {
                    const barcodes = await barcodeDetector.detect(video);
                    if (barcodes.length > 0) {
                        const code = barcodes[0].rawValue;
                        if (isValidIMEI(code)) {
                            document.getElementById('stock-imei').value = code;
                            showToast('✅ IMEI Scanned: ' + code);
                            toggleScanner(); // stop after successful scan
                            return;
                        }
                    }
                } catch (e) {}
            }
            requestAnimationFrame(scanLoop);
        }

        function isValidIMEI(imei) {
            // Basic IMEI validation: 15 digits, numeric
            return /^\d{14,17}$/.test(imei.replace(/\s/g, ''));
        }

        // ==================== EMPLOYEES ====================
        function addEmployee(e) {
            e.preventDefault();
            const name = document.getElementById('emp-name').value.trim();
            const phone = document.getElementById('emp-phone').value.trim();
            
            const employees = DB.get('employees');
            const id = 'emp_' + Date.now();
            
            employees.push({
                id, name, phone,
                createdAt: new Date().toISOString()
            });
            
            DB.set('employees', employees);
            
            document.getElementById('emp-name').value = '';
            document.getElementById('emp-phone').value = '';
            
            showToast('✅ Agent added successfully!');
            renderEmployees();
            populateAgentSelects();
            updateStats();
            logActivity(`Added agent: ${name}`);
        }

        function renderEmployees(filter = '') {
            const list = document.getElementById('employees-list');
            const employees = DB.get('employees');
            const filtered = employees.filter(e => 
                e.name.toLowerCase().includes(filter.toLowerCase()) ||
                e.phone.includes(filter)
            );
            
            if (filtered.length === 0) {
                list.innerHTML = `
                    <div class="empty-state">
                        <div class="icon">👤</div>
                        <h3>No agents found</h3>
                        <p>Add your first agent above</p>
                    </div>`;
                return;
            }
            
            list.innerHTML = filtered.map(emp => {
                const stockCount = DB.get('stock').filter(s => s.agentId === emp.id).length;
                return `
                    <div class="list-item">
                        <div class="list-item-info">
                            <div class="list-item-title">${emp.name}</div>
                            <div class="list-item-sub">📞 ${emp.phone}</div>
                        </div>
                        <span class="list-item-badge">${stockCount} phones</span>
                        <div class="list-item-actions">
                            <button class="icon-btn icon-btn-edit" onclick="viewAgentPhones('${emp.id}')" title="View Phones">📱</button>
                            <button class="icon-btn icon-btn-delete" onclick="deleteEmployee('${emp.id}')" title="Delete">🗑</button>
                        </div>
                    </div>`;
            }).join('');
        }

        function searchEmployees(query) {
            renderEmployees(query);
        }

        function deleteEmployee(id) {
            if (!confirm('Delete this agent? Their stock will be unallocated.')) return;
            
            let employees = DB.get('employees');
            const emp = employees.find(e => e.id === id);
            employees = employees.filter(e => e.id !== id);
            DB.set('employees', employees);
            
            // Unallocate their stock
            let stock = DB.get('stock');
            stock = stock.map(s => s.agentId === id ? { ...s, agentId: null, status: 'unallocated' } : s);
            DB.set('stock', stock);
            
            showToast('Agent deleted');
            renderEmployees();
            updateStats();
            logActivity(`Deleted agent: ${emp?.name || id}`);
        }

        function viewAgentPhones(empId) {
            const emp = DB.get('employees').find(e => e.id === empId);
            if (!emp) return;
            
            const phones = DB.get('stock').filter(s => s.agentId === empId);
            
            document.getElementById('modal-title').textContent = `${emp.name}'s Phones`;
            
            const content = document.getElementById('modal-content');
            if (phones.length === 0) {
                content.innerHTML = `<div class="empty-state"><div class="icon">📭</div><h3>No phones allocated</h3></div>`;
            } else {
                content.innerHTML = `
                    <div class="serials-list">
                        ${phones.map(p => `
                            <div class="serial-item">
                                <span>${p.imei}</span>
                                <span class="date">${p.model || 'Unknown model'}</span>
                            </div>
                        `).join('')}
                    </div>
                    <p style="margin-top: 16px; color: var(--text-light); font-size: 0.85rem;">
                        Total: ${phones.length} phone${phones.length > 1 ? 's' : ''}
                    </p>`;
            }
            
            document.getElementById('agent-modal').classList.add('active');
        }

        function closeModal() {
            document.getElementById('agent-modal').classList.remove('active');
        }

        // ==================== STOCK ====================
        function populateAgentSelects() {
            const employees = DB.get('employees');
            const selects = ['stock-agent', 'transfer-from', 'transfer-to'];
            
            selects.forEach(selId => {
                const sel = document.getElementById(selId);
                const currentVal = sel.value;
                sel.innerHTML = '<option value="">Select Agent...</option>';
                employees.forEach(emp => {
                    sel.innerHTML += `<option value="${emp.id}">${emp.name} (${emp.phone})</option>`;
                });
                if (currentVal) sel.value = currentVal;
            });
        }

        function allocateStock(e) {
            e.preventDefault();
            const imei = document.getElementById('stock-imei').value.trim().replace(/\s/g, '');
            const model = document.getElementById('stock-model').value.trim();
            const agentId = document.getElementById('stock-agent').value;
            
            if (!isValidIMEI(imei)) {
                showToast('❌ Invalid IMEI. Must be 14-17 digits.');
                return;
            }
            
            let stock = DB.get('stock');
            if (stock.some(s => s.imei === imei)) {
                showToast('❌ This IMEI already exists in system!');
                return;
            }
            
            const agent = DB.get('employees').find(e => e.id === agentId);
            
            stock.push({
                id: 'stk_' + Date.now(),
                imei,
                model: model || 'Unknown',
                agentId,
                status: 'allocated',
                allocatedAt: new Date().toISOString(),
                history: [{ action: 'allocated', to: agentId, date: new Date().toISOString() }]
            });
            
            DB.set('stock', stock);
            
            document.getElementById('stock-imei').value = '';
            document.getElementById('stock-model').value = '';
            document.getElementById('stock-agent').value = '';
            
            showToast(`✅ Stock allocated to ${agent?.name || 'agent'}!`);
            renderStock();
            updateStats();
            populateTransferSelects();
            logActivity(`Allocated ${imei} to ${agent?.name}`);
        }

        function renderStock(filter = '') {
            const list = document.getElementById('stock-list');
            const stock = DB.get('stock');
            const employees = DB.get('employees');
            
            const filtered = stock.filter(s => 
                s.imei.includes(filter) || 
                (s.model && s.model.toLowerCase().includes(filter.toLowerCase()))
            );
            
            if (filtered.length === 0) {
                list.innerHTML = `
                    <div class="empty-state">
                        <div class="icon">📦</div>
                        <h3>No stock found</h3>
                        <p>Add stock using the scanner above</p>
                    </div>`;
                return;
            }
            
            list.innerHTML = filtered.map(item => {
                const agent = employees.find(e => e.id === item.agentId);
                return `
                    <div class="list-item">
                        <div class="list-item-info">
                            <div class="list-item-title">${item.imei}</div>
                            <div class="list-item-sub">
                                ${item.model || 'Unknown model'} • 
                                ${agent ? '👤 ' + agent.name : '<span style="color:var(--danger)">Unallocated</span>'}
                            </div>
                        </div>
                        <div class="list-item-actions">
                            <button class="icon-btn icon-btn-delete" onclick="deleteStock('${item.id}')" title="Remove">🗑</button>
                        </div>
                    </div>`;
            }).join('');
        }

        function searchStock(query) {
            renderStock(query);
        }

        function deleteStock(id) {
            if (!confirm('Remove this phone from inventory?')) return;
            let stock = DB.get('stock');
            const item = stock.find(s => s.id === id);
            stock = stock.filter(s => s.id !== id);
            DB.set('stock', stock);
            showToast('Stock removed');
            renderStock();
            updateStats();
            populateTransferSelects();
            logActivity(`Removed stock: ${item?.imei}`);
        }

        // ==================== TRANSFER ====================
        function populateTransferSelects() {
            populateAgentSelects();
            loadTransferStock();
        }

        function loadTransferStock() {
            const fromId = document.getElementById('transfer-from').value;
            const phoneSel = document.getElementById('transfer-phone');
            phoneSel.innerHTML = '<option value="">Select Phone...</option>';
            
            if (!fromId) return;
            
            const stock = DB.get('stock').filter(s => s.agentId === fromId);
            stock.forEach(s => {
                phoneSel.innerHTML += `<option value="${s.id}">${s.imei} (${s.model || 'Unknown'})</option>`;
            });
        }

        function transferStock(e) {
            e.preventDefault();
            const fromId = document.getElementById('transfer-from').value;
            const toId = document.getElementById('transfer-to').value;
            const phoneId = document.getElementById('transfer-phone').value;
            
            if (fromId === toId) {
                showToast('❌ Cannot transfer to same agent!');
                return;
            }
            
            let stock = DB.get('stock');
            const item = stock.find(s => s.id === phoneId);
            const fromAgent = DB.get('employees').find(e => e.id === fromId);
            const toAgent = DB.get('employees').find(e => e.id === toId);
            
            if (!item) return;
            
            // Update stock
            item.agentId = toId;
            item.status = 'allocated';
            item.history = item.history || [];
            item.history.push({
                action: 'transferred',
                from: fromId,
                to: toId,
                date: new Date().toISOString()
            });
            
            DB.set('stock', stock);
            
            // Record transfer
            const transfers = DB.get('transfers');
            transfers.push({
                id: 'trf_' + Date.now(),
                phoneId,
                imei: item.imei,
                fromId,
                toId,
                date: new Date().toISOString()
            });
            DB.set('transfers', transfers);
            
            // Reset form
            document.getElementById('transfer-from').value = '';
            document.getElementById('transfer-to').value = '';
            document.getElementById('transfer-phone').innerHTML = '<option value="">Select Phone...</option>';
            
            showToast(`✅ Transferred to ${toAgent?.name}!`);
            renderTransferHistory();
            updateStats();
            renderStock();
            logActivity(`Transferred ${item.imei} from ${fromAgent?.name} to ${toAgent?.name}`);
        }

        function renderTransferHistory() {
            const list = document.getElementById('transfer-history');
            const transfers = DB.get('transfers').sort((a, b) => new Date(b.date) - new Date(a.date)).slice(0, 20);
            const employees = DB.get('employees');
            
            if (transfers.length === 0) {
                list.innerHTML = `
                    <div class="empty-state">
                        <div class="icon">🔄</div>
                        <h3>No transfers yet</h3>
                    </div>`;
                return;
            }
            
            list.innerHTML = transfers.map(t => {
                const from = employees.find(e => e.id === t.fromId);
                const to = employees.find(e => e.id === t.toId);
                const date = new Date(t.date).toLocaleString();
                return `
                    <div class="list-item">
                        <div class="list-item-info">
                            <div class="list-item-title">${t.imei}</div>
                            <div class="list-item-sub">
                                ${from?.name || 'Unknown'} → ${to?.name || 'Unknown'}<br>
                                <span style="font-size:0.75rem">${date}</span>
                            </div>
                        </div>
                    </div>`;
            }).join('');
        }

        // ==================== DASHBOARD ====================
        function updateStats() {
            const employees = DB.get('employees');
            const stock = DB.get('stock');
            
            document.getElementById('stat-agents').textContent = employees.length;
            document.getElementById('stat-phones').textContent = stock.length;
            document.getElementById('stat-instock').textContent = stock.filter(s => !s.agentId).length;
            document.getElementById('stat-allocated').textContent = stock.filter(s => s.agentId).length;
        }

        function quickSearch(query) {
            const results = document.getElementById('quick-search-results');
            if (!query.trim()) {
                results.innerHTML = '';
                return;
            }
            
            const employees = DB.get('employees');
            const stock = DB.get('stock');
            
            const matchedEmps = employees.filter(e => 
                e.name.toLowerCase().includes(query.toLowerCase()) ||
                e.phone.includes(query)
            );
            
            if (matchedEmps.length === 0) {
                results.innerHTML = '<p style="color: var(--text-light); text-align: center; padding: 20px;">No agents found</p>';
                return;
            }
            
            results.innerHTML = matchedEmps.map(emp => {
                const phones = stock.filter(s => s.agentId === emp.id);
                return `
                    <div class="list-item" style="cursor:pointer" onclick="viewAgentPhones('${emp.id}')">
                        <div class="list-item-info">
                            <div class="list-item-title">${emp.name}</div>
                            <div class="list-item-sub">📞 ${emp.phone} • ${phones.length} phone${phones.length !== 1 ? 's' : ''}</div>
                        </div>
                        <span style="font-size: 1.2rem;">→</span>
                    </div>`;
            }).join('');
        }

        function logActivity(msg) {
            const logs = DB.get('activity');
            logs.unshift({ msg, time: new Date().toISOString() });
            DB.set('activity', logs.slice(0, 50));
            renderRecentActivity();
        }

        function renderRecentActivity() {
            const list = document.getElementById('recent-activity');
            const logs = DB.get('activity').slice(0, 10);
            
            if (logs.length === 0) {
                list.innerHTML = '<p style="color: var(--text-light); text-align: center;">No recent activity</p>';
                return;
            }
            
            list.innerHTML = logs.map(l => `
                <div class="list-item">
                    <div class="list-item-info">
                        <div class="list-item-title" style="font-size: 0.9rem;">${l.msg}</div>
                        <div class="list-item-sub">${new Date(l.time).toLocaleString()}</div>
                    </div>
                </div>
            `).join('');
        }

        // Close modal on overlay click
        document.getElementById('agent-modal').addEventListener('click', (e) => {
            if (e.target.id === 'agent-modal') closeModal();
        });
    </script>
</body>
</html>
