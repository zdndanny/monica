<style scoped>
</style>

<template>

  <section class="ph3 ph5-ns pv3 w-100 bg-gray-monica">
    <div class="mw7 center pa4 br3 ba b--gray-monica bg-white">
      <form>
        <div class="tc bb b--black-20 mb3">
          <h3 class="f3">Log an activity</h3>
          <p class="measure center">Remember what you've done with one or more of your friends. The more details, the better.</p>
        </div>

        <div class="mb4">
          <p class="b mb2">What have you done?</p>
          <input type="text" name="" class="br3 b--black-40 ba pa3 w-100 f4" placeholder="Indicate...">
        </div>

        <div class="mb4">
          <p class="b mb2">Who were you with?</p>
          <input type="text" name="" class="br3 b--black-40 ba pa3 w-100 f4" placeholder="Indicate...">
        </div>

        <div class="mb4">
          <p class="b mb2">When was it?</p>
          <div class="br3 ba b--black-40">
            <label class="db pa3 bb b--black-20 mb0">
              <div class="">
                <span>Some time in the last 7 days</span>
              </div>
            </label>
            <label class="db pa3 mb0">
              <div class="">
                <span>Let me enter a date…</span>
              </div>
            </label>
          </div>
          <input type="text" name="" class="br3 b--gray-monica ba pa3 w-100 f4" placeholder="Indicate...">
        </div>


        Where did the activity take place?
        <div class="measure">
          <label for="name" class="f6 b db mb2">Name <span class="normal black-60">(optional)</span></label>
          <input id="name" class="input-reset ba b--black-20 pa2 mb2 db w-100" type="text" aria-describedby="name-desc">
          <small id="name-desc" class="f6 black-60 db mb2">Helper text for the form control.</small>
        </div>
      </form>

    </div>
  </section>

</template>

<script>
    export default {
        /*
         * The component's data.
         */
        data() {
            return {
            };
        },

        /**
         * Prepare the component (Vue 1.x).
         */
        ready() {
            this.prepareComponent();
        },

        /**
         * Prepare the component (Vue 2.x).
         */
        mounted() {
            this.prepareComponent();
        },

        methods: {
            /**
             * Prepare the component.
             */
            prepareComponent() {
            }
        }
    }
</script>
