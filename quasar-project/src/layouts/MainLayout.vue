<template>
  <div class="q-pa-md" style="max-width: 350px; height: 100vh;">
    <q-list bordered class="rounded-borders">
      <q-expansion-item
        expand-separator
        icon="mail"
        label="Inbox"
        caption="5 unread emails"
        default-opened
      >
        <q-expansion-item
          :header-inset-level="1"
          expand-separator
          icon="overview"
          label="Receipts"
          default-opened
        >

          <q-expansion-item switch-toggle-side dense-toggle label="Today" :header-inset-level="1" :content-inset-level="2">
         <q-expansion-item 
          expand-separator
          label="phone"
          default-opened>        
        </q-expansion-item>
          </q-expansion-item>



          <q-expansion-item switch-toggle-side dense-toggle label="Today" :header-inset-level="1" :content-inset-level="2">
         <q-expansion-item 
          expand-separator
          icon="phone"
          label="phone"
          default-opened></q-expansion-item>
          </q-expansion-item>
          <q-expansion-item switch-toggle-side dense-toggle label="Today" :header-inset-level="1" :content-inset-level="2">
         <q-expansion-item 
          expand-separator
          icon="phone"
          label="phone"
          default-opened></q-expansion-item>
          </q-expansion-item>
          <q-expansion-item switch-toggle-side dense-toggle label="Today" :header-inset-level="1" :content-inset-level="2">
         <q-expansion-item 
          expand-separator
          icon="phone"
          label="phone"
          default-opened></q-expansion-item>
          </q-expansion-item>
          <q-expansion-item switch-toggle-side dense-toggle label="Today" :header-inset-level="1" :content-inset-level="2">
         <q-expansion-item 
          expand-separator
          icon="phone"
          label="phone"
          default-opened></q-expansion-item>
          </q-expansion-item>
          <q-expansion-item switch-toggle-side dense-toggle label="Today" :header-inset-level="1" :content-inset-level="2">
         <q-expansion-item 
          expand-separator
          icon="phone"
          label="phone"
          default-opened></q-expansion-item>
          </q-expansion-item>
          <q-expansion-item switch-toggle-side dense-toggle label="Today" :header-inset-level="1" :content-inset-level="2">
         <q-expansion-item 
          expand-separator
          icon="phone"
          label="phone"
          default-opened></q-expansion-item>
          </q-expansion-item>
          <q-expansion-item switch-toggle-side dense-toggle label="Today" :header-inset-level="1" :content-inset-level="2">
         <q-expansion-item 
          expand-separator
          icon="phone"
          label="phone"
          default-opened></q-expansion-item>
          </q-expansion-item>

          <q-expansion-item switch-toggle-side dense-toggle label="Yesterday" :header-inset-level="1" :content-inset-level="2">
          <q-expansion-item 
          expand-separator
          icon="book"
          label="book"
          default-opened>
        </q-expansion-item>
          </q-expansion-item>

        </q-expansion-item>

        <q-expansion-item :header-inset-level="1" :content-inset-level="1" expand-separator icon="schedule" label="Postponed">
          <q-card>
            <q-card-section>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos corrupti
              commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto suscipit iste
              eveniet doloribus ullam aliquid.
            </q-card-section>
          </q-card>
        </q-expansion-item>

      </q-expansion-item>

      
    </q-list>
  </div>
</template>

<script>

</script>

<style lang="scss" scoped>

</style>