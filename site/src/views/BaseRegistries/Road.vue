<template>
  <vl-page>
    <vl-region mod-no-space-bottom>
      <vl-layout>
        <header class="wp-pt-heading">
          <div class="wp-pt-heading__parent">
            <vl-link to="/informatie" mod-bold>Basisregisters Vlaanderen</vl-link>
          </div>

          <div class="wp-pt-heading__title-wrapper">
            <vl-title tag-name="h1" class="wp-pt-heading__title">Wegenregister</vl-title>
          </div>

          <vl-grid>
            <vl-column width="9" width-s="12">
              <div class="wp-pt-heading__content">
                <vl-typography>
                  <vl-introduction>
                    Dit is een <strong>authentieke</strong> bron voor de Vlaamse wegen.
                  </vl-introduction>
                </vl-typography>
              </div>
            </vl-column>
          </vl-grid>
        </header>
      </vl-layout>
    </vl-region>

    <vl-main>
      <vl-region>
        <vl-layout>
          <vl-grid mod-stacked>
            <vl-column width="8" width-m="9" width-s="12">
              <vl-grid mod-stacked>
                <vl-column width="12">
                  <vl-title id="doel" tag-name="h2">Wat is het doel?</vl-title>

                  <vl-typography>
                    <p>Nog niet beschikbaar.</p>
                  </vl-typography>
                </vl-column>

                <vl-column width="12">
                  <vl-title id="status" tag-name="h2">Wat is de status?</vl-title>

                  <vl-typography>
                    <p>Nog niet beschikbaar.</p>
                  </vl-typography>
                </vl-column>

                <vl-column width="12">
                  <vl-title id="licentie" tag-name="h2">Welke licentie is van toepassing?</vl-title>

                  <vl-typography>
                    <p>Deze bron is gepubliceerd onder de <vl-link href="https://overheid.vlaanderen.be/sites/default/files/documenten/ict-egov/licenties/hergebruik/modellicentie_gratis_hergebruik_v1_0.html">&#8220;Modellicentie Gratis Hergebruik - v1.0&#8221;</vl-link>.</p>
                  </vl-typography>
                </vl-column>

                <vl-column width="12">
                  <vl-title id="documentatie" tag-name="h2">Hoe gebruik ik het?</vl-title>

                  <vl-typography>
                    <p>Deze bron kan momenteel nog niet aangesproken worden.</p>
                  </vl-typography>
                </vl-column>
              </vl-grid>
            </vl-column>

            <vl-column
              width="3"
              push="1"
              push-m="reset"
              width-s="12"
              class="wp-pt-side-navigation wp-pt-side-navigation--sticky-parent">
              <aside class="wp-pt-side-navigation--sticky" style="top: 120px;">
                <vl-side-navigation title="Op deze pagina">
                  <vl-side-navigation-list>
                    <vl-side-navigation-item href="#doel" text="Doel" />
                    <vl-side-navigation-item href="#status" text="Status" />
                    <vl-side-navigation-item href="#licentie" text="Licentie" />
                    <vl-side-navigation-item href="#documentatie" text="Documentatie" />
                  </vl-side-navigation-list>
                </vl-side-navigation>
              </aside>
            </vl-column>
          </vl-grid>
        </vl-layout>
      </vl-region>
    </vl-main>
  </vl-page>
</template>
