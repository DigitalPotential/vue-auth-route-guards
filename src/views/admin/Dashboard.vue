<template>
  <div class="dashboard">
    <h2>Dashboard</h2>
    <div class="stats-grid">
      <div class="stat-card">
        <h3>Total secrets</h3>
        <p class="stat">1</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  margin-top: 1rem;
}

.stat-card {
  background: white;
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.stat {
  font-size: 1.5rem;
  color: #42b983;
  font-weight: bold;
}
</style> 