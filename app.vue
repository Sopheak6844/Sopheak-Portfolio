<script setup lang="ts">
import { Analytics } from "@vercel/analytics/nuxt"
const route = useRoute()

/*
|--------------------------------------------------------------------------
| Global SEO Head
|--------------------------------------------------------------------------
*/

useHead({
  htmlAttrs: {
    lang: "en",
  },

  title: "Hun Sopheak | Web Developer & DevOps Cambodia",

  link: [
    { rel: "icon", type: "image/png", href: "/favicon-16.png" },
    {
      rel: "canonical",
      href: `https://sopheak.site${route.path === "/" ? "/" : route.path}`
    }
  ],

  meta: [
    {
      name: "google-site-verification",
      content: "370GbEZWEoxI2gp66i_pvfoAqP0ZUnyYas2E28C4-Q0"
    }
  ],

  script: [
    {
      type: "application/ld+json",
      children: JSON.stringify({
        "@context": "https://schema.org",
        "@type": "Person",
        name: "Hun Sopheak",
        url: "https://sopheak.site",
        image: "https://sopheak.site/hero.jpg",
        jobTitle: "Web Developer and DevOps Engineer",
        description:
          "Web Developer and DevOps Engineer in Cambodia specializing in Laravel, Nuxt, Kubernetes, Docker, and scalable cloud infrastructure.",
        worksFor: {
          "@type": "Organization",
          name: "Freelance"
        },
        address: {
          "@type": "PostalAddress",
          addressCountry: "Cambodia"
        },
        knowsAbout: [
          "Laravel",
          "Nuxt 3",
          "Docker",
          "Kubernetes",
          "CI/CD",
          "Terraform",
          "Cloud Infrastructure",
          "NGINX",
          "DevOps"
        ],
        sameAs: [
          "https://github.com/Sopheak6844",
          "https://linkedin.com/in/sopheak-hun/",
          "https://www.facebook.com/denki.hun"
        ]
      })
    }
  ]
})

/*
|--------------------------------------------------------------------------
| SEO Meta (OpenGraph + Twitter)
|--------------------------------------------------------------------------
*/

useSeoMeta({
  title: "Hun Sopheak | Web Developer & DevOps Cambodia",
  description:
    "Hun Sopheak is a Web Developer and DevOps Engineer in Cambodia specializing in Laravel, Nuxt, Kubernetes, CI/CD, Docker, and cloud infrastructure solutions.",
  
  ogTitle: "Hun Sopheak - Web Developer & DevOps Engineer in Cambodia",
  ogDescription:
    "Professional Web Developer and DevOps Engineer in Cambodia helping businesses build scalable and modern web applications.",
  ogImage: "https://sopheak.site/hero.jpg",
  ogUrl: `https://sopheak.site${route.path}`,
  ogType: "website",
  ogSiteName: "Hun Sopheak - Web Developer Cambodia",

  twitterCard: "summary_large_image",
  twitterTitle: "Hun Sopheak - DevOps Engineer in Cambodia",
  twitterDescription:
    "Laravel, Nuxt & DevOps specialist building scalable infrastructure and web applications.",
  twitterImage: "https://sopheak.site/hero.jpg"
})
</script>

<template>
  <div class="lenis-wrapper">
    <NuxtLayout>
      <Analytics />
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>