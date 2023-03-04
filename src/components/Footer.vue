<template>
  <div class="footer">
    <div class="container">
      <footer class="py-5" style="padding-bottom: 1rem !important">
        <div class="row">
          <div class="col-md-5 links footer_block">
            <img src="../assets/logo.webp" height="50 px" width="160px" />
            <br />

            <p>
              No. 1 of #Gaming in Tunisia, Gamers PCs & Pro Stations,
              accessories and components, the cheapest prices Telephone:

              <br />Prompay : 063-7875743
            </p>
          </div>

          <div class="col">
            <form>
              <h5>Subscribe to our newsletter</h5>
              <p>Monthly digest of what's new and exciting from us.</p>
              <div class="d-flex flex-column flex-sm-row w-100 gap-2">
                <label for="newsletter1" class="visually-hidden"
                  >Email address</label
                >
                <input
                  id="newsletter1"
                  type="text"
                  class="form-control"
                  placeholder="Email address"
                />
                <button
                  class="btn btn-primary"
                  type="button"
                  style="height: 38px; background-color: #C46B29"
                >
                  Subscribe
                </button>
              </div>
            </form>
          </div>
        </div>

      </footer>
    </div>
  </div>
</template>
<script>
export default {
  name: "FooterView",
};
</script>
<style>
.footer {
  background: #FFE199;
}
.py-5 {
  padding-top: 4rem !important;
  padding-bottom: 0rem !important;
}
</style>