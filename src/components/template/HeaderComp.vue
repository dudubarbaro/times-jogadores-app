<template>
  <header>
    <div class="menu-esquerdo">
      <span> <RouterLink to="/"> Home </RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/times"> Times </RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/jogadores"> Jogadores </RouterLink> </span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
</template>
<style>
header {
  background-color: darkred;
  color: white;
  height: 15%;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 2rem;
  justify-content: space-between;
}
header span {
  padding: 0 10px;
}
</style>
