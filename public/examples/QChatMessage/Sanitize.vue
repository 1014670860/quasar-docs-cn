<template>
  <div class="q-pa-md row justify-center">
    <div style="width: 100%; max-width: 400px">
      <q-chat-message
        name="<span class='text-positive'>不可信的来源</span>"
        avatar="https://cdn.quasar.dev/img/avatar3.jpg"
        :text="['hey, how are <strong>you</strong>?']"
        stamp="7 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="<span class='text-negative'>Jane (可信的 name 但是不可信的 text)</span>"
        name-html
        avatar="https://cdn.quasar.dev/img/avatar5.jpg"
        :text="[
          'doing fine, how r you?',
          'I just feel like typing a really, really, <strong>REALLY</strong> long message to annoy you...'
        ]"
        size="6"
        stamp="4 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="<span class='text-negative'>Jao (可信的)</span>"
        name-html
        avatar="https://cdn.quasar.dev/img/avatar5.jpg"
        :text="['<strong>Did it work?</strong>']"
        text-html
        stamp="1 minutes ago"
        size="8"
        text-color="white"
        bg-color="primary"
      />
    </div>
  </div>
</template>
