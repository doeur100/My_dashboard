<template>
  <link
    rel="stylesheet"
    href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0"
  />
  <div class="container-dashboard">
    <nav class="nav-bar">
      <h1>Good</h1>
    </nav>

    <div class="side-bar">
      <div>
        <span class="material-symbols-outlined"> home </span>
      </div>
      <div class="list-sidebar">
        <router-link to="/category" style="text-decoration: none; color: white">
          <span>Report</span></router-link
        >
        <span>Report</span>
        <span>Report</span>
        <span>Report</span>
        <span>Report</span>
        <span>Report</span>
        <span>Report</span>
        <span>Report</span>
        <span>Report</span>
        <span>Report</span>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-dashboard {
  margin-left: 14rem;
  margin-top: 6rem;
}
.nav-bar {
  padding: 0.2rem;
  position: fixed;
  top: 0;
  right: 0;
  left: 14rem;
  box-shadow: rgba(50, 50, 93, 0.25) 0px 2px 5px -1px,
    rgba(0, 0, 0, 0.3) 0px 1px 3px -1px;
}

.side-bar {
  background-color: rgba(0, 128, 128, 0.866);
  width: 14rem;
  height: 100rem;
  bottom: 0;
  position: absolute;
  left: 0;
  top: 0;
}
.side-bar .material-symbols-outlined {
  font-size: 4rem;
  display: flex;
  justify-content: center;
  margin-top: 2rem;
  color: white;
}
.list-sidebar {
  display: flex;
  flex-direction: column;
  padding: 20px;
  font-size: 25px;
  color: white;
}
.list-sidebar span {
  margin: 20px;
}
</style>
