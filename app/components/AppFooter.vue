<script setup lang="ts">
const year = new Date().getFullYear()
</script>

<template>
  <footer
    style="background-color: #1B3A6B"
    class="text-white"
  >
    <div class="max-w-6xl mx-auto px-4 py-10">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-8">
        <div>
          <div class="flex items-center gap-2 mb-4">
            <div class="w-8 h-8 bg-white/10 rounded-lg flex items-center justify-center">
              <UIcon
                name="i-lucide-shovel"
                class="text-white"
              />
            </div>
            <span class="font-bold text-white">MT 37 Terrassement</span>
          </div>
          <p class="text-blue-100 text-sm leading-relaxed mb-4">
            Entreprise de terrassement professionnelle en Indre-et-Loire. Excavation, nivellement, remblaiement dans tout le département 37.
          </p>
          <ul class="space-y-2 text-sm text-blue-100 mb-4">
            <li class="flex items-start gap-2">
              <UIcon
                name="i-lucide-phone"
                class="flex-shrink-0 mt-0.5"
              />
              <a
                href="tel:+33630996887"
                class="hover:text-white transition-colors font-semibold"
              >06 30 99 68 87</a>
            </li>
            <li class="flex items-start gap-2">
              <UIcon
                name="i-lucide-map-pin"
                class="flex-shrink-0 mt-0.5"
              />
              <span>24 rue des Rabatteries<br>37230 Fondettes</span>
            </li>
          </ul>
          <UButton
            to="https://share.google/NtX4H2KlUJb0We28G"
            target="_blank"
            rel="noopener"
            size="xs"
            label="Nos avis Google"
            icon="i-simple-icons-google"
            variant="outline"
            class="border-white/30 text-white hover:bg-white/10"
          />
        </div>

        <div>
          <h3 class="font-semibold text-white mb-4">
            Navigation
          </h3>
          <ul class="space-y-2 text-sm text-blue-100">
            <li>
              <NuxtLink
                to="/"
                class="hover:text-white transition-colors"
              >Accueil</NuxtLink>
            </li>
            <li>
              <NuxtLink
                to="/services"
                class="hover:text-white transition-colors"
              >Nos services</NuxtLink>
            </li>
            <li>
              <NuxtLink
                to="/zones"
                class="hover:text-white transition-colors"
              >Zones d'intervention</NuxtLink>
            </li>
            <li>
              <NuxtLink
                to="/contact"
                class="hover:text-white transition-colors"
              >Contact & devis</NuxtLink>
            </li>
            <li>
              <NuxtLink
                to="/mentions-legales"
                class="hover:text-white transition-colors"
              >Mentions légales</NuxtLink>
            </li>
          </ul>
        </div>

        <div>
          <h3 class="font-semibold text-white mb-4">
            Nos services
          </h3>
          <ul class="space-y-2 text-sm text-blue-100">
            <li class="flex items-start gap-2">
              <UIcon
                name="i-lucide-shovel"
                class="flex-shrink-0 mt-0.5"
              />
              Terrassement général
            </li>
            <li class="flex items-start gap-2">
              <UIcon
                name="i-lucide-construction"
                class="flex-shrink-0 mt-0.5"
              />
              Excavation & fouilles
            </li>
            <li class="flex items-start gap-2">
              <UIcon
                name="i-lucide-layers"
                class="flex-shrink-0 mt-0.5"
              />
              Nivellement & remblaiement
            </li>
            <li class="flex items-start gap-2">
              <UIcon
                name="i-lucide-hammer"
                class="flex-shrink-0 mt-0.5"
              />
              Démolition intérieure & extérieure
            </li>
            <li class="flex items-start gap-2 pt-2">
              <UIcon
                name="i-lucide-map-pin"
                class="flex-shrink-0 mt-0.5"
              />
              Indre-et-Loire (37) et environs
            </li>
          </ul>
        </div>
      </div>

      <div class="border-t border-white/10 pt-6 flex flex-col md:flex-row justify-between items-center gap-3 text-xs text-blue-200">
        <p>© {{ year }} MT 37 Terrassement — 24 rue des Rabatteries, 37230 Fondettes</p>
        <NuxtLink
          to="/mentions-legales"
          class="hover:text-white transition-colors"
        >Mentions légales</NuxtLink>
      </div>
    </div>
  </footer>
</template>
