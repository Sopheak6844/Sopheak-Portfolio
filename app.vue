<script setup lang="ts">
import { Analytics } from "@vercel/analytics/nuxt";
useHead({
  title: "Sopheak Hun | Web Developer & DevOps Engineer in Cambodia",
    meta: [
    {
      name: 'google-site-verification',
      content: '370GbEZWEoxI2gp66i_pvfoAqP0ZUnyYas2E28C4-Q0'
    }
  ],
  htmlAttrs: {
    lang: "en",
  },
  link: [
    { rel: "icon", type: "image/png", href: "/favicon-16.png" },
    { rel: "canonical", href: "https://sopheak.site/" }
  ],
  script: [
    {
      type: "application/ld+json",
      children: JSON.stringify({
        "@context": "https://schema.org",
        "@type": "Person",
        name: "Sopheak Hun",
        url: "https://sopheak.site",
        jobTitle: "Web Developer & DevOps Engineer",
        address: {
          "@type": "PostalAddress",
          addressCountry: "Cambodia"
        },
        sameAs: [
          "https://github.com/Sopheak6844",
          "https://linkedin.com/in/sopheak-hun/"
        ]
      })
    }
  ]
});


useSeoMeta({
title: "Sopheak Hun | Web Developer & DevOps Engineer in Cambodia",
  description:
    "Sopheak Hun is a Web Developer and DevOps Engineer based in Cambodia, specializing in Laravel, Nuxt, Kubernetes, and scalable cloud infrastructure solutions.",
  ogTitle: "Web Developer in Cambodia | Laravel & Nuxt - Sopheak Hun",
  ogDescription:
    "Professional Web Developer based in Cambodia specializing in Laravel, Nuxt, and DevOps solutions for businesses in Cambodia.",
  ogImage: "https://sopheak.site/hero.jpg",
  ogUrl: "https://sopheak.site/",
  ogType: "website",
  ogSiteName: "Sopheak Hun - Web Developer Cambodia",
  twitterCard: "summary_large_image",
  twitterTitle: "Web Developer in Cambodia - Sopheak Hun",
  twitterDescription:
    "Laravel, Nuxt & DevOps specialist helping Cambodian businesses build modern web applications.",
  twitterImage: "https://sopheak.site/hero.jpg",
});

</script>

<template>
  <div class="lenis-wrapper">
    <NuxtLayout>
      <Analytics />
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
