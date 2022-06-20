<template>
  <div class="home">
    <section class="section-1">
      <h1>Welcome to my Portfolio</h1>
      <div class="container">
        <img src="../assets/photo_aymeric.png" alt="photo-aymeric" />
        <div class="body">
          <h4>Aymeric Maillot</h4>
          <p>
            Hello, I’m a software engineer student in a Ingeneer school at Efrei
            PARIS since 2018. For several years I discover a reel passion of
            development Web and DevOps Culture. I like football, Video Games and
            Manga.
          </p>
        </div>
      </div>
    </section>
    <section class="section-2"></section>
    <section class="section-3">
      <h2>My skills</h2>
      <div class="container-skills">
        <div class="first-row">
          <div class="item">
            <img
              src="../assets/logo/logo_ghost_inspector.png"
              alt="ghostinspector"
            />
            <p>Ghost Inspector</p>
          </div>
          <div class="item">
            <img src="../assets/logo/logo_vue.png" alt="vuejs" />
            <p>Vue js</p>
          </div>
          <div class="item">
            <img src="../assets/logo/logo_js.png" alt="javascript" />
            <p>JavaScript</p>
          </div>
          <div class="item">
            <img src="../assets/logo/logo_github.png" alt="github" />
            <p>GitHub</p>
          </div>
        </div>
        <div class="second-row">
          <div class="item">
            <img src="../assets/logo/logo_express.png" alt="express" />
            <p>Express</p>
          </div>
          <div class="item">
            <img src="../assets/logo/logo_css.png" alt="css" />
            <p>Css</p>
          </div>
          <div class="item">
            <img src="../assets/logo/logo_html.png" alt="html" />
            <p>Html</p>
          </div>
          <div class="item">
            <img src="../assets/logo/logo_mysql.png" alt="mysql" />
            <p>MySql</p>
          </div>
        </div>
        <div class="third-row">
          <div class="item">
            <img src="../assets/logo/logo_jira.png" alt="jira" />
            <p>Jira</p>
          </div>
          <div class="item">
            <img src="../assets/logo/logo_confluence.png" alt="confluence" />
            <p>Confluence</p>
          </div>
          <div class="item">
            <img src="../assets/logo/logo_mongodb.png" alt="mongodb" />
            <p>MongoDB</p>
          </div>
          <div class="item">
            <img src="../assets/logo/logo_firebase.png" alt="mysql" />
            <p>Firebase</p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  components: {},
})
export default class HomeView extends Vue {}
</script>

<style lang="scss" scoped>
.home {
  font-family: "Fira Sans";
  .section-1 {
    background-color: #202948;
    height: 90vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    h1 {
      font-style: normal;
      font-weight: 400;
      font-size: 70px;
      line-height: 108px;
      color: #fff;
      padding: 2rem;
    }

    .container {
      margin: 2rem;
      width: 70%;
      height: 309px;
      background: #2b355c;
      color: #fff;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;

      img {
        margin: 1rem;
        width: 211.46px;
        height: 215.45px;
        border-radius: 100px;
        transform: matrix(1, -0.01, 0.01, 1, 0, 0);
      }

      .body {
        height: 100%;
        width: 100%;
        h4 {
          width: 534.99px;
          font-style: normal;
          font-weight: 400;
          font-size: 38px;
          line-height: 58px;
          color: #ffffff;
          text-align: start;
        }
        p {
          width: 691.48px;
          height: 208.28px;
          font-style: normal;
          font-weight: 400;
          font-size: 20px;
          line-height: 36px;
          color: #ffffff;
          text-align: start;
        }
      }
    }
  }

  .section-2 {
    height: 100vh;
    background: #2b355c;
  }

  .section-3 {
    background-color: #202948;
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;

    h2 {
      font-size: 40px;
      margin: auto;
      color: #fff;
    }

    .container-skills {
      display: flex;
      flex-direction: column;
      margin: auto 0;

      .first-row,
      .second-row,
      .third-row {
        display: flex;

        .item {
          color: #3e4f97;
          flex-direction: column;
          background: #2b355c;
          border-radius: 50%;
          margin: 1rem;
          display: flex;
          justify-content: center;
          align-items: center;
          height: 180px;
          width: 180px;
          font-size: 20px;
          font-weight: 700;

          img {
            margin: 1rem 0;
            height: 65px;
            width: 65px;
          }
        }
      }
    }
  }
}
</style>
