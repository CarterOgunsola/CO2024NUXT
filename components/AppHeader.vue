<template>
  <header>
    <nav class="nav_wrap">
      <div class="nav_contain container">
        <div class="row row-justify-between">
          <div class="col col-lg-3">
            <div class="nav_logo_wrap">
              <div class="nav_logo_flex">
                <div class="nav_logo_icon_wrap">
                  <div class="nav_logo_icon_line"></div>
                  <svg
                    class="nav_logo_icon"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M8 16C12.5027 16 16 12.6067 16 8.01074C16 3.41477 12.5027 0 8 0C3.49727 0 0 3.41477 0 8.01074C0 12.6067 3.49727 16 8 16ZM8 15.1624C4 15.1624 1.00546 12.1342 1.00546 8.01074C1.00546 3.88725 4 0.837585 8 0.837585C12 0.837585 14.9945 3.88725 14.9945 8.01074C14.9945 12.1342 12 15.1624 8 15.1624ZM8.06557 12.9074C9.37705 12.9074 10.3169 12.5208 10.9945 11.898C11.6721 11.2752 12.0656 10.3517 12.0874 9.47114H10.4699C10.3388 10.6309 9.5082 11.5329 8.06557 11.5329C6.29508 11.5329 5.15847 10.0725 5.15847 7.98926C5.15847 5.94899 6.14208 4.38121 8.06557 4.38121C9.37705 4.38121 10.1858 5.08993 10.3825 6.14228H12.0437C11.8033 4.40269 10.4044 3.00671 8.08743 3.00671C5.20219 3.00671 3.45355 5.15436 3.45355 7.98926C3.45355 10.8456 5.33333 12.9074 8.06557 12.9074Z"
                      fill="white"
                    />
                  </svg>
                </div>
                <div class="nav_logo_text_wrap">
                  <a class="u-mb-0 eyebrow u-text-white"
                    ><nuxt-link to="/">THE CARTER OGUNSOLA</nuxt-link></a
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="col col-lg-3">
            <div>
              <a><nuxt-link to="/">Home</nuxt-link></a>
              <a><nuxt-link to="/about">About</nuxt-link></a>
              <a><nuxt-link to="/projects">Projects</nuxt-link></a>
              <a><nuxt-link to="/contact">Contact</nuxt-link></a>
            </div>
          </div>
          <div class="col col-lg-1">
            <p>Sound</p>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>
