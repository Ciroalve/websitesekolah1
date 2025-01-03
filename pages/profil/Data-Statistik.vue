<template>
    <div> class="container-fluid">
      <div class="row">
        <div> class="col-lg-12">
            <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
              Statistik Data <b>SMKN 4 TASIKMALAYA</b>
            </h5>
          </div>
          <div class="col-lg-12">
            <p style="background-color: whitesmoke;" class="rounded-3 p-1 m-3 text-secondary">
              <NuxtLink to="/profil" class="text-decoration-none">Profil</NuxtLink>/ Statistik Data
            </p>
          </div>
          <!-- Statistik Data -->
        <div class="col-lg-12 mb-3">
          <div class="card">
            <div class="card-header bg-light">
              <h5 class="text-center">Statistik Data</h5>
            </div>
            <div class="card-body">
              <div class="row">
                <!-- Jumlah Siswa -->
                <div class="col-md-6 mb-3">
                  <div class="card bg-success text-white text-center">
                    <div class="card-body">
                      <h6>Jumlah Siswa</h6>
                      <h3>1610</h3>
                    </div>
                  </div>
                </div>
                <!-- Jumlah Rombel -->
                <div class="col-md-6 mb-3">
                  <div class="card bg-danger text-white text-center">
                    <div class="card-body">
                      <h6>Jumlah Rombel</h6>
                      <h3>41</h3>
                    </div>
                  </div>
                </div>
                <!-- Jumlah Guru -->
                <div class="col-md-6 mb-3">
                  <div class="card bg-warning text-white text-center">
                    <div class="card-body">
                      <h6>Jumlah Guru</h6>
                      <h3>82</h3>
                    </div>
                  </div>
                </div>
                <!-- Jumlah Tenaga Administrasi -->
                <div class="col-md-6 mb-3">
                  <div class="card bg-info text-white text-center">
                    <div class="card-body">
                      <h6>Jumlah Tenaga Administrasi</h6>
                      <h3>12</h3>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>

<<style scoped>
/* Global Styles */
body {
  font-family: Arial, sans-serif;
  background-color: #f8f9fa;
  margin: 0;
  padding: 0;
}

.container-fluid {
  padding: 20px;
}

h5, h6, h3, p {
  margin: 0;
}

/* Header Styles */
.text-white {
  color: #fff !important;
}

.text-secondary {
  color: #6c757d !important;
}

.text-center {
  text-align: center !important;
}

.rounded-3 {
  border-radius: 16px !important;
}

.p-2, .p-1 {
  padding: 0.5rem !important;
}

.m-3 {
  margin: 1rem !important;
}

/* Link Styles */
.text-decoration-none {
  text-decoration: none !important;
}

.text-decoration-none:hover {
  text-decoration: underline;
  color: #000;
}

/* Card Styles */
.card {
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  border: none;
  border-radius: 16px;
}

.card-header {
  font-size: 1.25rem;
  font-weight: bold;
}

.card-body h6 {
  font-size: 1rem;
  margin-bottom: 0.5rem;
}

.card-body h3 {
  font-size: 2.5rem;
  font-weight: bold;
}

.bg-light {
  background-color: #f8f9fa !important;
}

.bg-success {
  background-color: #28a745 !important;
}

.bg-danger {
  background-color: #dc3545 !important;
}

.bg-warning {
  background-color: #ffc107 !important;
}

.bg-info {
  background-color: #17a2b8 !important;
}

/* Media Queries */
@media (max-width: 768px) {
  .card-body h3 {
    font-size: 2rem;
  }
  .card-body h6 {
    font-size: 0.9rem;
  }
}
</style>
