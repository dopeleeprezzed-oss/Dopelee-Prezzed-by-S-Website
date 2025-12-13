<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dopelee Prezzed - Ops Dashboard</title>
  <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
  
  <style>
    /* ═══════════════════════════════════════════════════════════════ */
    /* DOPELEE OPS DASHBOARD - COMPLETE STYLES */
    /* ═══════════════════════════════════════════════════════════════ */
    
    /* RESET & BASE */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
      background: #0b0c0f;
      color: #e8e8ec;
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* HEADER */
    .dashboard-header {
      background: linear-gradient(135deg, #0a95a8, #3461fa, #fd26fd, #d3fb1b);
      padding: 2rem;
      text-align: center;
      box-shadow: 0 4px 20px rgba(10, 149, 168, 0.3);
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .dashboard-logo {
      max-width: 200px;
      height: auto;
      margin: 0 auto 1rem;
      display: block;
      filter: drop-shadow(0 2px 8px rgba(0, 0, 0, 0.3));
    }

    @media (max-width: 768px) {
      .dashboard-logo {
        max-width: 150px;
      }
    }

    .brand-title {
      font-size: 2rem;
      font-weight: 800;
      color: #ffffff;
      text-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
      margin-bottom: 0.5rem;
    }

    .tagline {
      font-size: 1rem;
      font-style: italic;
      color: #ffffff;
      opacity: 0.9;
      margin-bottom: 1.5rem;
    }

    .header-actions {
      display: flex;
      gap: 1rem;
      justify-content: center;
      flex-wrap: wrap;
    }

    /* BUTTONS */
    .btn {
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 8px;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      transition: all 0.3s ease;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }

    .btn-primary {
      background: #0a95a8;
      color: #ffffff;
    }

    .btn-primary:hover {
      background: #088799;
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(10, 149, 168, 0.4);
    }

    .btn-secondary {
      background: #3461fa;
      color: #ffffff;
    }

    .btn-secondary:hover {
      background: #2850e0;
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(52, 97, 250, 0.4);
    }

    .btn-sm {
      padding: 0.3rem 0.6rem;
      font-size: 0.8rem;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 600;
    }

    /* LOADING */
    .loading {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 60vh;
      gap: 1rem;
    }

    .spinner {
      width: 50px;
      height: 50px;
      border: 4px solid rgba(10, 149, 168, 0.1);
      border-top: 4px solid #0a95a8;
      border-radius: 50%;
      animation: spin 1s linear infinite;
    }

    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    /* DASHBOARD LAYOUT */
    .dashboard {
      max-width: 1400px;
      margin: 0 auto;
      padding: 2rem;
    }

    /* SCORECARDS */
    .scorecards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin-bottom: 2rem;
    }

    .scorecard {
      background: rgba(18, 19, 25, 0.8);
      backdrop-filter: blur(10px);
      border: 2px solid transparent;
      border-radius: 16px;
      padding: 1.5rem;
      text-align: center;
      transition: all 0.3s ease;
      position: relative;
      overflow: hidden;
    }

    .scorecard::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      border-radius: 16px;
      padding: 2px;
      background: linear-gradient(135deg, #0a95a8, #d3fb1b, #fd26fd, #3461fa);
      -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
      -webkit-mask-composite: xor;
      mask-composite: exclude;
      opacity: 0;
      transition: opacity 0.3s ease;
    }

    .scorecard:hover::before {
      opacity: 1;
    }

    .scorecard:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 30px rgba(10, 149, 168, 0.3);
    }

    .scorecard-icon {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    .scorecard-label {
      font-size: 0.9rem;
      color: #b8bac0;
      text-transform: uppercase;
      letter-spacing: 1px;
      margin-bottom: 0.5rem;
    }

    .scorecard-value {
      font-size: 2.5rem;
      font-weight: 800;
      background: linear-gradient(135deg, #0a95a8, #d3fb1b);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    /* TRAFFIC LIGHTS */
    .traffic-lights {
      background: rgba(18, 19, 25, 0.6);
      border-radius: 16px;
      padding: 1.5rem;
      margin-bottom: 2rem;
      border: 1px solid #2a2a2a;
    }

    .section-title {
      font-size: 1.5rem;
      margin-bottom: 1rem;
      color: #ffffff;
    }

    .traffic-container {
      display: flex;
      gap: 2rem;
      justify-content: space-around;
      flex-wrap: wrap;
    }

    .traffic-item {
      display: flex;
      align-items: center;
      gap: 0.75rem;
      padding: 1rem;
      border-radius: 12px;
      background: rgba(255, 255, 255, 0.05);
      transition: all 0.3s ease;
      cursor: pointer;
    }

    .traffic-item:hover {
      transform: scale(1.05);
      background: rgba(255, 255, 255, 0.1);
    }

    .traffic-icon {
      font-size: 2rem;
    }

    .traffic-label {
      font-size: 1rem;
      font-weight: 600;
    }

    .traffic-count {
      font-size: 1.5rem;
      font-weight: 800;
      margin-left: auto;
    }

    .traffic-item.green .traffic-count {
      color: #00ff00;
    }

    .traffic-item.yellow .traffic-count {
      color: #ffff00;
    }

    .traffic-item.red .traffic-count {
      color: #ff0000;
    }

    /* CHARTS */
    .charts-section {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
      gap: 2rem;
      margin-bottom: 2rem;
    }

    .chart-container {
      background: rgba(18, 19, 25, 0.8);
      border-radius: 16px;
      padding: 1.5rem;
      border: 1px solid #2a2a2a;
    }

    .chart-title {
      font-size: 1.2rem;
      margin-bottom: 1rem;
      color: #d3fb1b;
      text-align: center;
    }

    /* RECENT ORDERS TABLE */
    .recent-orders {
      background: rgba(18, 19, 25, 0.6);
      border-radius: 16px;
      padding: 1.5rem;
      border: 1px solid #2a2a2a;
    }

    .table-container {
      overflow-x: auto;
      margin-top: 1rem;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    thead {
      background: #0a95a8;
    }

    th {
      padding: 1rem;
      text-align: left;
      font-weight: 700;
      color: #ffffff;
      text-transform: uppercase;
      font-size: 0.85rem;
      letter-spacing: 0.5px;
    }

    tbody tr {
      border-bottom: 1px solid #2a2a2a;
      transition: background 0.2s ease;
    }

    tbody tr:hover {
      background: rgba(10, 149, 168, 0.1);
    }

    td {
      padding: 1rem;
      color: #e8e8ec;
    }

    .status-badge {
      display: inline-block;
      padding: 0.25rem 0.75rem;
      border-radius: 20px;
      font-size: 0.85rem;
      font-weight: 600;
      text-transform: uppercase;
    }

    .status-confirmed {
      background: rgba(0, 255, 0, 0.2);
      color: #00ff00;
    }

    .status-production {
      background: rgba(255, 255, 0, 0.2);
      color: #ffff00;
    }

    .status-shipped {
      background: rgba(52, 97, 250, 0.2);
      color: #3461fa;
    }

    /* ERROR STATE */
    .error-state {
      text-align: center;
      padding: 3rem;
      color: #ff0000;
    }

    .error-state h2 {
      margin-bottom: 1rem;
    }

    /* RESPONSIVE */
    @media (max-width: 768px) {
      .brand-title {
        font-size: 1.5rem;
      }
      
      .scorecards {
        grid-template-columns: 1fr;
      }
      
      .charts-section {
        grid-template-columns: 1fr;
      }
      
      .traffic-container {
        flex-direction: column;
      }
      
      table {
        font-size: 0.85rem;
      }
      
      th, td {
        padding: 0.5rem;
      }
    }
  </style>
</head>
<body>
  <!-- HEADER -->
  <header class="dashboard-header">
    <div class="header-content">
      <h1 class="brand-title">🖤 DOPELEE PREZZED OPS DASHBOARD</h1>
    </div>
    <div class="header-actions">
      <button class="btn btn-primary" onclick="generateCommissionReport()">
        💰 Commission Report
      </button>
      <button class="btn btn-secondary" onclick="refreshDashboard()">
        🔄 Refresh
      </button>
    </div>
  </header>

  <!-- LOADING STATE -->
  <div id="loading" class="loading">
    <div class="spinner"></div>
    <p>Loading dashboard data...</p>
  </div>

  <!-- MAIN DASHBOARD -->
  <main id="dashboard" class="dashboard" style="display: none;">
    
    <!-- SCORECARDS -->
    <section class="scorecards">
      <div class="scorecard">
        <div class="scorecard-icon">📦</div>
        <div class="scorecard-label">Orders This Month</div>
        <div class="scorecard-value" id="ordersThisMonth">0</div>
      </div>
      
      <div class="scorecard">
        <div class="scorecard-icon">💰</div>
        <div class="scorecard-label">Revenue This Month</div>
        <div class="scorecard-value" id="revenueThisMonth">$0</div>
      </div>
      
      <div class="scorecard">
        <div class="scorecard-icon">🔨</div>
        <div class="scorecard-label">In Production</div>
        <div class="scorecard-value" id="inProduction">0</div>
      </div>
      
      <div class="scorecard">
        <div class="scorecard-icon">📦</div>
        <div class="scorecard-label">Shipped This Week</div>
        <div class="scorecard-value" id="shippedThisWeek">0</div>
      </div>
    </section>

    <!-- TRAFFIC LIGHTS -->
    <section class="traffic-lights">
      <h2 class="section-title">🚦 Production Status</h2>
      <div class="traffic-container">
        <div class="traffic-item green">
          <span class="traffic-icon">🟢</span>
          <span class="traffic-label">On Time</span>
          <span class="traffic-count" id="onTimeCount">0</span>
        </div>
        <div class="traffic-item yellow">
          <span class="traffic-icon">🟡</span>
          <span class="traffic-label">Due Soon</span>
          <span class="traffic-count" id="dueSoonCount">0</span>
        </div>
        <div class="traffic-item red">
          <span class="traffic-icon">🔴</span>
          <span class="traffic-label">Overdue</span>
          <span class="traffic-count" id="overdueCount">0</span>
        </div>
      </div>
    </section>

    <!-- CHARTS -->
    <section class="charts-section">
      <div class="chart-container">
        <h3 class="chart-title">Orders by Status</h3>
        <canvas id="statusChart"></canvas>
      </div>
      
      <div class="chart-container">
        <h3 class="chart-title">Revenue by Product</h3>
        <canvas id="revenueChart"></canvas>
      </div>
    </section>

    <!-- RECENT ORDERS -->
    <section class="recent-orders">
      <h2 class="section-title">📋 Recent Orders</h2>
      <div class="table-container">
        <table id="ordersTable">
          <thead>
            <tr>
              <th>Order ID</th>
              <th>Customer</th>
              <th>Honoree</th>
              <th>Product</th>
              <th>Status</th>
              <th>Created</th>
              <th>Days Old</th>
              <th>Actions</th>
            </tr>
          </thead>
          <tbody id="ordersTableBody">
            <!-- Populated by JavaScript -->
          </tbody>
        </table>
      </div>
    </section>

  </main>

  <!-- ERROR STATE -->
  <div id="error" class="error-state" style="display: none;">
    <h2>⚠️ Error Loading Dashboard</h2>
    <p id="errorMessage"></p>
    <button class="btn btn-primary" onclick="refreshDashboard()">Try Again</button>
  </div>

  <script>
    // ═══════════════════════════════════════════════════════════════
    // DOPELEE ADMIN DASHBOARD - SUPABASE VERSION (FIXED)
    // ═══════════════════════════════════════════════════════════════

    // SUPABASE CONFIG
    const SUPABASE_URL = 'https://zgnceundsigimwujwrzu.supabase.co';
    const SUPABASE_KEY = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InpnbmNldW5kc2lnaW13dWp3cnp1Iiwicm9sZSI6ImFub24iLCJpYXQiOjE3NjQ5OTA5MzQsImV4cCI6MjA4MDU2NjkzNH0.Vdl9J8D_kkmxhPq1QwU33g__b1_AGNF';

    // Global data storage
    let allOrders = [];
    let currentFilter = 'all';

    // Initialize dashboard
    document.addEventListener('DOMContentLoaded', () => {
      console.log('🚀 Dashboard loading...');
      loadDashboardData();
      setupFilters();
    });

    /**
     * Setup filter buttons
     */
    function setupFilters() {
      const filterHTML = `
        <div style="display: flex; gap: 1rem; margin: 1rem 0; justify-content: center; flex-wrap: wrap;">
          <button class="btn btn-secondary" onclick="filterOrders('all')">All Orders</button>
          <button class="btn btn-secondary" onclick="filterOrders('pending')">⚡ Pending Form</button>
          <button class="btn btn-secondary" onclick="filterOrders('production')">🔨 In Production</button>
          <button class="btn btn-secondary" onclick="filterOrders('shipped')">📦 Shipped</button>
        </div>
      `;
      
      const recentOrdersSection = document.querySelector('.recent-orders');
      if (recentOrdersSection) {
        recentOrdersSection.insertAdjacentHTML('afterbegin', filterHTML);
      }
    }

    /**
     * Filter orders by status
     */
    function filterOrders(filter) {
      currentFilter = filter;
      updateRecentOrders();
    }

    /**
     * Filter by traffic light status
     */
    function filterByDueStatus(status) {
      if (status === 'ontime') {
        currentFilter = 'ontime';
      } else if (status === 'duesoon') {
        currentFilter = 'duesoon';
      } else if (status === 'overdue') {
        currentFilter = 'overdue';
      }
      updateRecentOrders();
      
      // Scroll to orders table
      document.querySelector('.recent-orders').scrollIntoView({ behavior: 'smooth' });
    }

    /**
     * Load data from Supabase
     */
    async function loadDashboardData() {
      showLoading();
      
      try {
        console.log('📡 Fetching from Supabase...');
        
        const response = await fetch(`${SUPABASE_URL}/rest/v1/orders?select=*&order=created_at.desc`, {
          headers: {
            'apikey': SUPABASE_KEY,
            'Authorization': `Bearer ${SUPABASE_KEY}`
          }
        });
        
        if (!response.ok) {
          throw new Error(`API Error: ${response.status} ${response.statusText}`);
        }
        
        const data = await response.json();
        allOrders = data || [];
        
        console.log(`✅ Loaded ${allOrders.length} orders`);
        
        updateDashboard();
        showDashboard();
        
      } catch (error) {
        console.error('❌ Error loading data:', error);
        showError(error.message);
      }
    }

    /**
     * Show order details modal
     */
    function showOrderDetails(order) {
      const last4 = order.order_id ? order.order_id.slice(-4) : 'Unknown';
      
      const details = `
📋 ORDER DETAILS #${last4}

👤 CUSTOMER INFO:
Name: ${order.customer_name || 'N/A'}
Email: ${order.customer_email || 'N/A'}
Phone: ${order.customer_phone || 'N/A'}

💝 KEEPSAKE INFO:
Honoring: ${order.honored_name || 'N/A'}
Dates: ${order.dates || 'N/A'}
Product: ${order.product_type || 'N/A'}
Template: ${order.template_chosen || 'N/A'}
Orientation: ${order.orientation || 'N/A'}

✍️ PERSONALIZATION:
${order.custom_wording || 'N/A'}

📝 DESIGNER NOTES:
${order.designer_notes || 'N/A'}

📸 PHOTO:
${order.photo_url ? 'Uploaded ✓' : 'Not uploaded'}

💰 ORDER INFO:
Total: $${order.order_total || '0'}
Status: ${order.status || 'Unknown'}
Payment Status: ${order.payment_status || 'N/A'}
Form Complete: ${order.form_complete ? 'Yes' : 'No'}

📅 DATES:
Created: ${order.created_at ? new Date(order.created_at).toLocaleString() : 'N/A'}
Updated: ${order.updated_at ? new Date(order.updated_at).toLocaleString() : 'N/A'}

🔗 PORTAL LINK:
${order.portal_link || 'N/A'}
      `;
      
      alert(details);
    }

    /**
     * Update order status with dropdown
     */
    async function updateOrderStatus(orderId, currentStatus) {
      const statusOptions = [
        'Payment Received',
        'Form Received',
        'In Production',
        'Shipped',
        'Delivered',
        'Custom Message'
      ];
      
      let message = 'Select new status:\n\n';
      statusOptions.forEach((opt, i) => {
        message += `${i + 1}. ${opt}\n`;
      });
      
      const choice = prompt(message + '\nEnter number (1-6):');
      
      if (!choice) return;
      
      const index = parseInt(choice) - 1;
      
      if (index < 0 || index >= statusOptions.length) {
        alert('❌ Invalid choice');
        return;
      }
      
      let newStatus = statusOptions[index];
      
      // If custom message selected
      if (newStatus === 'Custom Message') {
        newStatus = prompt('Enter custom status message:');
        if (!newStatus) return;
      }
      
      // If "Shipped" selected, ask for tracking number
      let trackingNumber = null;
      if (newStatus === 'Shipped') {
        trackingNumber = prompt('📦 Enter tracking number:');
        if (!trackingNumber) {
          alert('❌ Tracking number required for shipped orders');
          return;
        }
      }
      
      try {
        const updateData = {
          status: newStatus,
          updated_at: new Date().toISOString()
        };
        
        // Add tracking number if provided
        if (trackingNumber) {
          updateData.tracking_number = trackingNumber;
        }
        
        const response = await fetch(`${SUPABASE_URL}/rest/v1/orders?order_id=eq.${orderId}`, {
          method: 'PATCH',
          headers: {
            'apikey': SUPABASE_KEY,
            'Authorization': `Bearer ${SUPABASE_KEY}`,
            'Content-Type': 'application/json',
            'Prefer': 'return=representation'
          },
          body: JSON.stringify(updateData)
        });
        
        if (!response.ok) throw new Error('Failed to update status');
        
        const successMsg = trackingNumber 
          ? `✅ Status updated to: ${newStatus}\n📦 Tracking: ${trackingNumber}`
          : `✅ Status updated to: ${newStatus}`;
        
        alert(successMsg);
        loadDashboardData();
        
      } catch (error) {
        console.error('Error updating status:', error);
        alert('❌ Error updating status');
      }
    }

    /**
     * Update all dashboard components
     */
    function updateDashboard() {
      updateScorecards();
      updateTrafficLights();
      updateCharts();
      updateRecentOrders();
    }

    /**
     * Update scorecard values
     */
    function updateScorecards() {
      const now = new Date();
      const thisMonth = now.getMonth();
      const thisYear = now.getFullYear();
      const startOfWeek = getStartOfWeek(now);
      
      const ordersThisMonth = allOrders.filter(order => {
        const createdDate = new Date(order.created_at);
        return createdDate.getMonth() === thisMonth && 
               createdDate.getFullYear() === thisYear;
      }).length;
      
      const revenueThisMonth = allOrders
        .filter(order => {
          const createdDate = new Date(order.created_at);
          return createdDate.getMonth() === thisMonth && 
                 createdDate.getFullYear() === thisYear;
        })
        .reduce((sum, order) => sum + (parseFloat(order.order_total) || 0), 0);
      
      const inProduction = allOrders.filter(order => {
        const status = order.status || '';
        return status.includes('Form Received') || status.includes('Production');
      }).length;
      
      const shippedThisWeek = allOrders.filter(order => {
        const status = order.status || '';
        const updatedDate = new Date(order.updated_at);
        return status.includes('Shipped') && updatedDate >= startOfWeek;
      }).length;
      
      animateValue('ordersThisMonth', 0, ordersThisMonth, 1000);
      animateValue('revenueThisMonth', 0, revenueThisMonth, 1000, true);
      animateValue('inProduction', 0, inProduction, 1000);
      animateValue('shippedThisWeek', 0, shippedThisWeek, 1000);
    }

    /**
     * Update traffic light counts - CLICKABLE
     */
    function updateTrafficLights() {
      let onTime = 0;
      let dueSoon = 0;
      let overdue = 0;
      
      const now = new Date();
      
      allOrders.forEach(order => {
        const status = order.status || '';
        
        if (status.includes('Form Received') || status.includes('Production')) {
          const createdDate = new Date(order.created_at);
          const daysOld = Math.floor((now - createdDate) / (1000 * 60 * 60 * 24));
          const daysLeft = 7 - daysOld;
          
          if (daysLeft > 2) onTime++;
          else if (daysLeft >= 0 && daysLeft <= 2) dueSoon++;
          else overdue++;
        }
      });
      
      document.getElementById('onTimeCount').textContent = onTime;
      document.getElementById('dueSoonCount').textContent = dueSoon;
      document.getElementById('overdueCount').textContent = overdue;
      
      // Make traffic lights clickable
      const trafficItems = document.querySelectorAll('.traffic-item');
      if (trafficItems[0]) trafficItems[0].onclick = () => filterByDueStatus('ontime');
      if (trafficItems[1]) trafficItems[1].onclick = () => filterByDueStatus('duesoon');
      if (trafficItems[2]) trafficItems[2].onclick = () => filterByDueStatus('overdue');
      
      // Add titles
      trafficItems.forEach(item => {
        item.title = 'Click to filter orders';
      });
    }

    /**
     * Create charts
     */
    function updateCharts() {
      createStatusChart();
      createRevenueChart();
    }

    function createStatusChart() {
      const statusCounts = {};
      allOrders.forEach(order => {
        const status = order.status || 'Unknown';
        statusCounts[status] = (statusCounts[status] || 0) + 1;
      });
      
      const ctx = document.getElementById('statusChart').getContext('2d');
      if (window.statusChartInstance) window.statusChartInstance.destroy();
      
      window.statusChartInstance = new Chart(ctx, {
        type: 'doughnut',
        data: {
          labels: Object.keys(statusCounts),
          datasets: [{
            data: Object.values(statusCounts),
            backgroundColor: ['#0a95a8', '#d3fb1b', '#fd26fd', '#3461fa', '#0ff0b8', '#ff6b6b'],
            borderWidth: 2,
            borderColor: '#0b0c0f'
          }]
        },
        options: {
          responsive: true,
          plugins: {
            legend: {
              position: 'bottom',
              labels: { color: '#e8e8ec', font: { size: 12 } }
            }
          }
        }
      });
    }

    function createRevenueChart() {
      const productRevenue = {};
      allOrders.forEach(order => {
        const product = order.product_type || 'Keepsake';
        productRevenue[product] = (productRevenue[product] || 0) + (parseFloat(order.order_total) || 0);
      });
      
      const ctx = document.getElementById('revenueChart').getContext('2d');
      if (window.revenueChartInstance) window.revenueChartInstance.destroy();
      
      window.revenueChartInstance = new Chart(ctx, {
        type: 'bar',
        data: {
          labels: Object.keys(productRevenue),
          datasets: [{
            label: 'Revenue ($)',
            data: Object.values(productRevenue),
            backgroundColor: '#0a95a8',
            borderColor: '#d3fb1b',
            borderWidth: 2
          }]
        },
        options: {
          responsive: true,
          scales: {
            y: {
              beginAtZero: true,
              ticks: {
                color: '#e8e8ec',
                callback: value => '$' + value.toLocaleString()
              },
              grid: { color: 'rgba(255, 255, 255, 0.1)' }
            },
            x: {
              ticks: { color: '#e8e8ec' },
              grid: { color: 'rgba(255, 255, 255, 0.1)' }
            }
          },
          plugins: {
            legend: { labels: { color: '#e8e8ec' } }
          }
        }
      });
    }

    /**
     * Update recent orders table
     */
    function updateRecentOrders() {
      const tableBody = document.getElementById('ordersTableBody');
      tableBody.innerHTML = '';
      
      let filteredOrders = allOrders;
      
      // Filter logic
      if (currentFilter === 'pending') {
        filteredOrders = allOrders.filter(o => o.status === 'Payment Received' && !o.form_complete);
      } else if (currentFilter === 'production') {
        filteredOrders = allOrders.filter(o => o.status?.includes('Form Received') || o.status?.includes('Production'));
      } else if (currentFilter === 'shipped') {
        filteredOrders = allOrders.filter(o => o.status?.includes('Shipped'));
      } else if (currentFilter === 'ontime' || currentFilter === 'duesoon' || currentFilter === 'overdue') {
        const now = new Date();
        filteredOrders = allOrders.filter(order => {
          const status = order.status || '';
          if (!status.includes('Form Received') && !status.includes('Production')) return false;
          
          const createdDate = new Date(order.created_at);
          const daysOld = Math.floor((now - createdDate) / (1000 * 60 * 60 * 24));
          const daysLeft = 7 - daysOld;
          
          if (currentFilter === 'ontime') return daysLeft > 2;
          if (currentFilter === 'duesoon') return daysLeft >= 0 && daysLeft <= 2;
          if (currentFilter === 'overdue') return daysLeft < 0;
        });
      }
      
      const displayOrders = filteredOrders.slice(0, 20);
      
      if (displayOrders.length === 0) {
        tableBody.innerHTML = '<tr><td colspan="8" style="text-align: center; padding: 2rem;">No orders found</td></tr>';
        return;
      }
      
      displayOrders.forEach(order => {
        const tr = document.createElement('tr');
        
        const orderId = order.order_id ? `#${order.order_id.slice(-4)}` : 'N/A';
        const customer = order.customer_email || order.customer_name || 'N/A';
        const honoree = order.honored_name || 'N/A';
        const product = order.product_type || 'Keepsake';
        const status = order.status || 'Unknown';
        const createdDate = order.created_at ? formatDate(new Date(order.created_at)) : 'N/A';
        const daysOld = order.created_at ? Math.floor((new Date() - new Date(order.created_at)) / (1000 * 60 * 60 * 24)) : 'N/A';
        
        let statusClass = 'status-badge ';
        if (status.includes('Payment')) statusClass += 'status-confirmed';
        else if (status.includes('Form') || status.includes('Production')) statusClass += 'status-production';
        else if (status.includes('Shipped')) statusClass += 'status-shipped';
        
        // Escape quotes for JSON in onclick
        const orderJSON = JSON.stringify(order).replace(/"/g, '&quot;');
        
        tr.innerHTML = `
          <td>${orderId}</td>
          <td style="max-width: 150px; overflow: hidden; text-overflow: ellipsis;">${customer}</td>
          <td>${honoree}</td>
          <td>${product}</td>
          <td><span class="${statusClass}">${status}</span></td>
          <td>${createdDate}</td>
          <td>${daysOld} days</td>
          <td>
            <div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
              <button class="btn-sm" onclick='updateOrderStatus("${order.order_id}", "${status}")' style="background: #0a95a8; color: #fff;">📝 STATUS</button>
              <button class="btn-sm" onclick='showOrderDetails(${orderJSON})' style="background: #fd26fd; color: #fff;">📋 DETAILS</button>
            </div>
          </td>
        `;
        
        tableBody.appendChild(tr);
      });
    }

    /**
     * Refresh dashboard
     */
    function refreshDashboard() {
      loadDashboardData();
    }

    /**
     * Generate commission report
     */
    function generateCommissionReport() {
      alert('Commission report feature coming soon! 💰');
    }

    /**
     * UTILITY FUNCTIONS
     */
    function formatDate(date) {
      return date ? date.toLocaleDateString('en-US', { month: '2-digit', day: '2-digit', year: 'numeric' }) : 'N/A';
    }

    function getStartOfWeek(date) {
      const d = new Date(date);
      const day = d.getDay();
      return new Date(d.setDate(d.getDate() - day));
    }

    function animateValue(id, start, end, duration, isCurrency = false) {
      const element = document.getElementById(id);
      const startTime = performance.now();
      
      function update(currentTime) {
        const elapsed = currentTime - startTime;
        const progress = Math.min(elapsed / duration, 1);
        const current = Math.floor(start + (end - start) * progress);
        
        element.textContent = isCurrency ? '$' + current.toLocaleString() : current.toLocaleString();
        
        if (progress < 1) requestAnimationFrame(update);
      }
      
      requestAnimationFrame(update);
    }

    function showLoading() {
      document.getElementById('loading').style.display = 'flex';
      document.getElementById('dashboard').style.display = 'none';
      document.getElementById('error').style.display = 'none';
    }

    function showDashboard() {
      document.getElementById('loading').style.display = 'none';
      document.getElementById('dashboard').style.display = 'block';
      document.getElementById('error').style.display = 'none';
    }

    function showError(message) {
      document.getElementById('loading').style.display = 'none';
      document.getElementById('dashboard').style.display = 'none';
      document.getElementById('error').style.display = 'block';
      document.getElementById('errorMessage').textContent = message;
    }
  </script>
</body>
</html>
