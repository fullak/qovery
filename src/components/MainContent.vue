<template>
    <div class="main-content">

            <div class="first-content">
                <h2 class="content-title">How does it work?</h2>
                <p class="content-text">Qovery Engine is an open-source abstraction layer product that turns easy apps deployment on AWS, GCP, Azure and others Cloud providers. The Qovery Engine is coded in Rust and takes advantage of Terraform, Helm, Kubectl, Docker to manage resources.</p>
                <img src="../assets/img/howItWork.png" alt="" class="first-content-img">
            </div>

            <div class="second-content">
                <h2 class="content-title">Usage</h2>
                <p class="content-text">Initialize EKS (AWS Kubernetes) and ECR (AWS container registry) on AWS</p>
                <img src="../assets/img/code-img.png" alt="" class="second-content-img">
            </div>

            <div class="btn-container">
                <a href="#"><img src="../assets/img/githubBtn.png" alt=""></a>
                <a href="#"><img src="../assets/img/discordBtn.png" alt=""></a>
            </div>

            <div class="third-content">
                <article class="first-article">
                    <img src="../assets/img/Illu/1.png" alt="" class="article-img">
                    <h2 class="article-title">Deploy real world applications</h2>
                    <p class="article-text">Qovery Engine empowers you to deploy complex applications, such as a backend, a frontend, and a database in a very simple way. Servers, networking, security, all is done by the Engine for you.</p>
                    <a href="#" class="article-link">SEE MORE</a>
                </article>

                <article class="second-article">
                    <img src="../assets/img/Illu/2.png" alt="" class="article-img">
                    <h2 class="article-title">Resiliency is key</h2>
                    <p class="article-text">Qovery Engine knows when something goes wrong on the deployment of your applications. Qovery Engine is built with resiliency in mind. <br>
                    <br>
                    A transactional engine inspired by what is provided into ACID databases has been developed at the heart of the product to rollback on a consistent and working application version when something goes wrong. </p>
                    <a href="#" class="article-link">SEE MORE</a>
                </article>

                <artcile class="third-article">
                    <img src="../assets/img/Illu/3.png" alt="" class="article-img">
                    <h2 class="article-title">On top of the best tools</h2>
                    <p class="article-text">Qovery Engine does not reinvent the wheel. It takes advantage of the best tools in the Cloud industry, such as Kubernetes, Terraform, and Helm to manage the deployment of the infrastructure and your applications. <br>
                    <br>
                        Servers, networking, security, all is done by the Engine for you.</p>
                    <a href="#" class="article-link">SEE MORE</a>
                </artcile>

                <article class="fourth-article">
                    <img src="../assets/img/Illu/4.png" alt="" class="article-img">
                    <h2 class="article-title">Extensible</h2>
                    <p class="article-text">Qovery Engine is built to be highly extensible. Adding the support of a Cloud provider or a Continuous Integration platform is as simple as implementing a simple programmatic interface.  </p>
                    <a href="#" class="article-link">SEE MORE</a>
                </article>
            </div>

            <h2 class="last-title">They use Qovery Engine</h2>

    </div>
</template>

<script>
export default {
    name: 'main-content',
}
</script>

<style scoped>
.main-content{
    background-color: #F9F9FD;
    height: auto;
    padding: 10px;
}

.first-content-img{
    width: 100%;
    margin: 20px 0;
}

.second-content{
    padding-top: 20px;
    background-image: url('../assets/img/background-second.png');
    background-size: 100%;
    background-repeat: no-repeat;
    background-position: top;
    background-position-x: 10px;
    background-position-y: 60px;
}

.second-content-img {
    width: 100%;
    margin-top: -10px;
}

.btn-container {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin: 20px auto;
}

.article-title,
.article-text {
    text-align: left;
}

.article-link{
    float: left;
}

.article-img {
    width: 80%;
    margin: 50px auto;
}

.last-title{
    margin: 100px auto 20px;
}

@media screen and (min-width: 700px) {

    .main-content{
        padding: 0 100px;
    }

    .second-content{
    background-image: url('../assets/img/background-second.png');
    background-size: 100%;
    background-position-x: 30px;
    padding-top: 50px;
    }

    .second-content-img {
    width: 100%;
    margin-top: 80px;
    }

    .btn-container{
        padding: 0 120px;
    }

    .third-content {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-between;
    }

    .first-article,
    .second-article,
    .third-article,
    .fourth-article {
        width: 40%;
    }

    .article-img {
        width: 150px;
        height: 150px;
    }

    .last-title{
        padding-bottom: 70px;
    }

}

@media screen and (min-width: 1025px) {

    .main-content{
        padding: 0 350px;
    }

    .btn-container {
        padding: 0 250px 50px;
    }

    .article-img {
        height: 200px;
        width: 200px;
    }
}
</style>