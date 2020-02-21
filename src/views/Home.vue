<template lang="pug">
  .home
    img(alt="Vue logo" src="../assets/logo.png")
    my-select(
    :options="options"
    )

</template>

<script>
  import MySelect from '@/components/MySelect';

  export default {
    name: 'Home',
    components: {
      MySelect,
    },
    data: () => ({
      options: [
        'abc', 'cde'
      ]
    })
  };
</script>
