<template lang="">
    <div className='header'>
      <nav>
        <ul>
          <RouterLink to="/" active-class="nav-active">
            <li>Selamat datang</li>
          </RouterLink>
          <RouterLink to="/userlist" active-class="nav-active">
            <li>Favorit</li>
          </RouterLink>

        </ul>
      </nav>
      <h1>VueJS Aries Movies</h1>
    </div>
</template>