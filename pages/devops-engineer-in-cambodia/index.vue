<script setup lang="ts">
const route = useRoute()

useSeoMeta({
  title: "DevOps Engineer in Cambodia – Hun Sopheak",
  description:
    "Hun Sopheak is a DevOps Engineer in Cambodia specializing in Kubernetes, Docker, CI/CD pipelines, Terraform, and scalable cloud infrastructure solutions."
})

useHead({
  link: [
    {
      rel: "canonical",
      href: "https://www.sopheak.site/devops-engineer-in-cambodia"
    }
  ],
  script: [
    {
      type: "application/ld+json",
      children: JSON.stringify({
        "@context": "https://schema.org",
        "@type": "FAQPage",
        mainEntity: [
          {
            "@type": "Question",
            name: "What does a DevOps Engineer do?",
            acceptedAnswer: {
              "@type": "Answer",
              text: "A DevOps Engineer designs and manages infrastructure, automates deployments, implements CI/CD pipelines, and ensures system scalability and reliability."
            }
          },
          {
            "@type": "Question",
            name: "Do you provide Kubernetes setup in Cambodia?",
            acceptedAnswer: {
              "@type": "Answer",
              text: "Yes, I provide Kubernetes cluster setup, Docker containerization, and production-ready deployment solutions in Cambodia."
            }
          },
          {
            "@type": "Question",
            name: "Can you build CI/CD pipelines from scratch?",
            acceptedAnswer: {
              "@type": "Answer",
              text: "Yes, I build complete CI/CD pipelines using GitHub Actions, GitLab CI, and Jenkins for automated deployment workflows."
            }
          }
        ]
      })
    }
  ]
})
</script>

<template>
  <main class="container">
    <h1>Hun Sopheak – DevOps Engineer in Cambodia</h1>

    <section>
      <p>
        I am a DevOps Engineer in Cambodia specializing in building scalable,
        secure, and automated infrastructure for modern web applications.
        With experience in cloud deployment, CI/CD pipeline automation,
        container orchestration, and infrastructure as code, I help
        businesses improve system reliability and deployment efficiency.
      </p>
    </section>

    <section>
      <h2>CI/CD Pipeline Automation</h2>
      <p>
        I design and implement continuous integration and continuous deployment
        pipelines using GitHub Actions, GitLab CI, and Jenkins. My CI/CD
        workflows automate code testing, Docker image builds, and zero-downtime
        deployments to production environments.
      </p>
    </section>

    <section>
      <h2>Containerization & Kubernetes</h2>
      <p>
        Using Docker and Kubernetes, I containerize applications and manage
        scalable production environments. I configure Kubernetes clusters
        with proper networking, resource limits, scaling strategies, and
        monitoring systems to ensure high availability.
      </p>
    </section>

    <section>
      <h2>Infrastructure as Code</h2>
      <p>
        I use Terraform to provision and manage infrastructure in a
        version-controlled manner. Infrastructure as Code ensures repeatable
        deployments, improved security, and scalable cloud architecture.
      </p>
    </section>

    <section>
      <h2>Monitoring & Performance Optimization</h2>
      <p>
        I implement monitoring stacks using tools such as Prometheus and
        Grafana to track performance, uptime, and resource utilization.
        Proper monitoring enables proactive issue detection and system stability.
      </p>
    </section>

    <section>
      <h2>Why Hire a DevOps Engineer in Cambodia?</h2>
      <p>
        Hiring a local DevOps Engineer in Cambodia provides better
        communication, regional business understanding, and cost-effective
        infrastructure solutions. I work with startups and growing businesses
        to design reliable systems that scale efficiently.
      </p>
    </section>

    <section>
      <h2>Frequently Asked Questions</h2>

      <h3>What does a DevOps Engineer do?</h3>
      <p>
        A DevOps Engineer automates development and deployment processes,
        manages cloud infrastructure, and ensures scalable and reliable systems.
      </p>

      <h3>Do you provide Kubernetes setup in Cambodia?</h3>
      <p>
        Yes, I provide full Kubernetes cluster configuration and Docker-based
        deployment solutions.
      </p>

      <h3>Can you build CI/CD pipelines from scratch?</h3>
      <p>
        Yes, I build automated CI/CD workflows tailored to your project
        requirements.
      </p>
    </section>
  </main>
</template>

<style scoped>
.container {
  max-width: 900px;
  margin: auto;
  padding: 2rem;
  line-height: 1.7;
}

h1 {
  margin-bottom: 1.5rem;
}

section {
  margin-bottom: 2.5rem;
}

h2 {
  margin-bottom: 1rem;
}

h3 {
  margin-top: 1rem;
}
</style>