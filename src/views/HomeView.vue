<template>
  <main>
    <h1>Главная</h1>

    <section>
      <ul>
        <li>
          <router-link :to="{ name: 'settings' }"> Настройки </router-link>
        </li>

        <li>
          <router-link :to="{ name: 'user', params: { id: 123 } }">
            Пользователь 123
          </router-link>
        </li>
      </ul>
    </section>
  </main>
</template>
