<script setup></script>

<template>
  <div class="w-[800px] mx-auto">
    <div class="mt-20">
      <div class="input-box gap-4">
        <input
          class="px-5 py-2 rounded border border-slate-600 bg-slate-900"
          type="text"
          placeholder="Напиши что-нибудь"
        />
        <button
          class="px-5 py-2 rounded bg-emerald-500 transition hover:bg-emerald-400"
        >
          Принять
        </button>
      </div>
      
      <div class="mt-8">
        <div>
          <div
            class="flex items-center justify-between py-5 px-8 rounded bg-slate-900"
          >
            <p>Заметка</p>
            <div class="flex gap-1">
              <button
                class="px-5 py-2 rounded bg-emerald-500 transition hover:bg-emerald-400"
              >
                Завершить
              </button>
              <button
                class="px-5 py-2 rounded bg-cyan-500 transition hover:bg-cyan-400"
              >
                Редактировать
              </button>
              <button
                class="px-5 py-2 rounded bg-red-500 transition hover:bg-red-400"
              >
                Удалить
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  .input-box {
    display: grid;
    grid-template-columns: 2fr 1fr;
  }
</style>
