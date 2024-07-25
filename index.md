---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>
    .title-tagline{
        color: #ffcc00;
        font-weight: bold;
        font-size: 2.5rem;
        text-align: center;
        margin-top: 16px;
    }
    .title-head{
        font-weight: bold;
        font-size: 1.4rem;
        text-align: center;
        color: #e5f0f8;
    }
    .text-body{
        font-weight: normal;
        font-size: 1.2rem;
        text-align: left;
        color: #e5f0f8;
    }
    .text-dark{
        color: #0b113a;
        font-size: 1.25rem;
        text-align: center;
    }
    .card{
        flex: 1;
        margin: 8px;
        padding: 8px;
        background-color: rgba(240, 240, 240, 0.3);
        border-radius: 2px;
        border-width: 2px 0px 2px 0px;
        border-style: solid;
        border-color: #ffcc00;
    }
    .card-img{
        display: block;
        width:100%;
        object-fit: contain;
        margin: auto;
        border-radius: 8px;
    }
    .card-head{
        width: 100%;
        text-align: center;
        margin-bottom: 4px;
        font-size: 2rem;
    }
    .card-body{
        font-size: 1.25rem;
        margin: 16px;
    }
    #main-table { 
        display: flex;
        flex-direction: row;
        width: 75%;
        margin: auto;
    }

    @media screen and (max-width: 900px) {
        .title-tagline {
            font-size: 2rem;
        }
        .card-head {
            font-size: 1.5rem;
        }
        .card-body {
            font-size: 1rem;
            margin: 4px;
        }
        #main-table { 
            width: 90%;
        }
    }

    @media screen and (max-width: 600px) {
        .text-dark {
            font-size: 1rem;
        }
        .card-head {
            font-size: 1.75rem;
        }
        .card-body {
            font-size: 1.25rem;
            margin: 16px;
        }
        #main-table { 
            display: flex;
            flex-direction: column;
        }
    }
</style>

<div>
    <img id="img-logo" src="./assets/img/logo-dark-transparent.png" alt="logo" style="display: block; width:60%; object-fit: contain; margin: auto; padding-bottom: 16px"/>
</div>
___
<div style="padding-bottom: 12px" class="title-tagline">Raising the bar.</div>
<div class="text-dark" style="background-color: #f0f0f0; padding: 24px; border-radius: 8px 8px 0px 0px; border-width: 4px 2px 0px 2px; border-style: solid; border-color: #ffcc00">
The performance team at the <span style="font-weight:bold">Sports Trauma & Applied Research Lab</span> conducts research focused on the health & performance of team sport athletes, all the way from evaluation to optimization.
</div>
<br>
<div id="main-table">
    <div class="card">
        <div class="card-head">Evaluation</div>
        <div>
            <img src="./assets/img/01-eval.png" alt="img1" class="card-img"/>
        </div>
        <div class="card-body">Systematically assess athletes through cutting-edge technology & comprehensive physiological metrics.</div>
    </div>
    <div class="card">
        <div class="card-head">Prevention</div>
        <div>
            <img src="./assets/img/02-prevent.png" alt="img2" class="card-img"/>
        </div>
        <div class="card-body">Proactively mitigate athlete injuries through personalized & evidence-based methods to foster sustained performance.</div>
    </div>
    <div class="card">
        <div class="card-head">Optimization</div>
        <div>
            <img src="./assets/img/03-optim.png" alt="img3" class="card-img"/>
        </div>
        <div class="card-body">Maximize athlete performance through personalized, data-driven analyses, to ensure both athletes & teams reach their full potential.</div>
    </div>
</div>
<br>
<div style="background-color: #f0f0f0; padding: 24px; border-radius: 0px 0px 8px 8px; border-width: 0px 2px 4px 2px; border-style: solid; border-color: #ffcc00">
    <div class="text-dark" style="font-weight: bold; font-size: 1.4rem; text-align: center;">Lab Director</div>
    <div class="text-dark" style="font-weight: 600; font-style: italic; font-size: 1.2rem; text-align: center;">Dr. Louis De Beaumont</div>
    <div class="text-dark" style="text-align: left">
        Dr. Louis de Beaumont specializes in researching concussions and traumatic brain injuries, with a focus on their effects in athletes. His work examines changes in brain structure and function post-concussion and explores biomarkers for prevention, diagnosis, and treatment.
    </div>
</div>
