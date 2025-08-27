<script setup>
// Use the error layout (no header/footer)
definePageMeta({
  layout: 'error',
})

// Set page title
useHead({
  title: 'Link Expired - Sink',
})
</script>

<template>
  <NuxtLayout name="error">
    <div class="min-h-screen bg-gradient-to-br from-gray-50 to-gray-100 dark:from-gray-900 dark:to-gray-800 flex items-center justify-center p-4">
      <div class="max-w-md w-full text-center">
        <!-- Icon -->
        <div class="mb-8">
          <div class="mx-auto w-24 h-24 bg-red-100 dark:bg-red-900/20 rounded-full flex items-center justify-center">
            <svg
              class="w-12 h-12 text-red-600 dark:text-red-400"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-2.5L13.732 4c-.77-.833-1.964-.833-2.732 0L4.732 15.5c-.77.833.192 2.5 1.732 2.5z"
              />
            </svg>
          </div>
        </div>

        <!-- Content -->
        <div class="mb-8">
          <h1 class="text-3xl font-bold text-gray-900 dark:text-white mb-3">
            Link Expired
          </h1>
          <p class="text-gray-600 dark:text-gray-300 text-lg mb-4">
            Sorry, this link has expired or is no longer available.
          </p>
          <p class="text-gray-500 dark:text-gray-400 text-sm">
            The link you're looking for might have been removed, had its name changed, or is temporarily unavailable.
          </p>
        </div>
      </div>
    </div>
  </NuxtLayout>
</template>
