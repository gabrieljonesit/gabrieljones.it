---
layout: default
title: Homepage di esempio
description: Questo è un esempio di homepage con utilizzo del componente "hero"
lang: it
ref: homepage
permalink: /
order: 1
---

{% include hero.html %}

<section class="section bg-white py-2 py-lg-3 py-xl-5">
        <div class="container">
          <div class="row variable-gutters">
            <div class="col-lg-4">
              <div class="title-section pb-4">
                <h2>Progetti</h2>
              </div><!-- /title-section -->
              <div class="card card-bg card-vertical-thumb bg-white card-thumb-rounded">
                <div class="card-body">
                  <div class="card-content">
                    <h3 class="h5">
                      <a href="https://edu.arenagiovani.it/capitolo-notturno/">Capitolo notturno</a>
                    </h3>
                    <p>"Capitolo notturno" è un gruppo di lettura promosso da "Arena Giovani | Ufficio Cultura".</p>
                  </div>
                </div><!-- /card-body -->
                <div class="card-comments-wrapper">
                  <div class="card-avatar-img">
                    <img src="https://edu.gabrieljones.it/assets/placeholders/img-avatar-250x250.png" alt="Immagine profilo">
                  </div><!-- /card-avatar-img -->
                  <div class="card-avatar-content">
                    <p class="font-weight-normal">da <a href="https://comune.arenagiovani.it/persone/presidentoffice/" aria-label="vai alla pagina Matteo Enea Bianchi"><strong class="text-underline"><u>Matteo</u></strong></a></p>
                    <small>Referente di ufficio</small>
                  </div><!-- /card-avatar-content -->
                </div><!-- /card-comments-wrapper -->
              </div><!-- /card -->
              <div class="py-4">
                <a aria-label="Leggi tutte le notizie" class="text-underline" href="https://edu.arenagiovani.it/capitolo-notturno/"><strong>Leggi tutte</strong></a>
              </div>
            </div>
          </div><!-- /row -->
        </div><!-- /container -->
      </section>
