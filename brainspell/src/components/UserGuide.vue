<template>
  <div id="user-guide" class="pt-4">

    <h1> User Guide </h1>
    <div class="container intro">
        <div class="row align-items-center pt-3">
            <div class="col-md-8">
            <p>
                This is a guide to getting started with MetaCurious. To contribute to development, check out our <a href="#/developerguide">Developer Guide</a>.
            </p>
            <p>
                Before you start you'll need to set up a free <a href="https://github.com/" target="_blank">GitHub</a> account, if you don't already have one, and sign in.
                Here are some <a href="https://help.github.com/articles/signing-up-for-a-new-github-account" target="_blank">instructions</a>.
            </p>
            <p>
                You should login to MetaCurious with your GitHub account.
            </p>
            </div>
            <div class="col-md-4">
                <img src="../assets/imgs/undraw_collab.svg" class="undraw">
            </div>
        </div>
    </div>
  </div>
</template>

<style>
    .intro {
        text-align: left;
        padding: 1.5em 3em 0 3em;
    }

    .undraw {
        width: 100%;
    }

</style>

<script>
export default {
  name: 'user-guide',
  data() {
    return {
      count: 1,
    };
  },
};
</script>
