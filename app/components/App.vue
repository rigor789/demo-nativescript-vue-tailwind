<template>
    <Page>
        <ActionBar title="Welcome to NativeScript-Vue!"/>
        <StackLayout class="space-y-4 divide-y-4 divide-red-500">
            <Label text="Hello Tailwind!" class="p-4 bg-red-400 bg-opacity-25" />
            <Label text="Hello Tailwind!" class="p-4 bg-red-400 bg-opacity-50" />
            <Label text="Hello Tailwind!" class="p-4 bg-red-400 bg-opacity-75" />
            <Label text="Hello Tailwind!" class="p-4 bg-blue-400 bg-opacity-25" />
            <Label text="Hello Tailwind!" class="p-4 bg-blue-400 bg-opacity-50" />
        </StackLayout>
    </Page>
</template>

<script >
  export default {
    data() {
      return {
        msg: 'Hello World!'
      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
</style>
