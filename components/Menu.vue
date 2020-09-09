<template>
  <nav class="menu navbar navbar-expand-sm">
    <ul class="menu__list navbar-nav">
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/`">Home</n-link>
      </li>
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/#services`">Our Services</n-link>
      </li>
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/#gallery`">Gallery</n-link>
      </li>
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/#reviews`">Reviews</n-link>
      </li>
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/#faq`">FAQs</n-link>
      </li>
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" :to="`/#about`">About Us</n-link>
      </li>
      <li class="menu__item nav-item ml-5">
        <n-link class="nav-link" to="`/#contact-form`">Contact Us</n-link>
      </li>
    </ul>
  </nav>
</template>
