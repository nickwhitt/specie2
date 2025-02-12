<template>
  <article>
    <UBreadcrumb :items="[
      { label: 'Federal Types', to: '/federal' },
      { label: 'Cents', to: '/federal/cents' },
      { label: 'Lincoln Cents' },
    ]" />

    <ProseH1>Lincoln Cents</ProseH1>

    <TypeDetail title="Wheat Ears Reverse (1909-1958)" slug="wheat-ears" :images="[
      '/cents/lincoln-wheat-obv.webp',
      '/cents/lincoln-wheat-rev.webp',
    ]">
      <ProseP>
        Lincoln Wheat cents designed by Victor D. Brenner debuted in 1909 and were the first circulating U.S. coins to
        picture an actual person. The Wheat Ears reverse ended in 1958, while the obverse portrait has endured as the
        Mint's longest running design. All Wheat cents are struck in bronze except for 1943 issues struck in steel.
      </ProseP>
      <UButtonGroup class="-ms-2.5">
        <TypeSpecifications title="Wheat Cent Specifications" :data="{
          designer: 'Victor D. Brenner',
          weight: '3.11 grams // 1943: 2.70 grams',
          composition: 'bronze (.950 copper, .050 tin and zinc) // 1943: zinc-coated steel',
          diameter: '19 mm',
          edge: 'Plain',
        }" />
        <UModal title="Wheat Cent Issues">
          <UButton variant="link">Issues</UButton>
          <template #body></template>
        </UModal>
      </UButtonGroup>
    </TypeDetail>

    <TypeDetail title="Memorial Reverse (1959-2008)" slug="memorial" :images="[]">
      <ProseP>
        In 1959, for the 150th anniversary of Lincoln's birth, the reverse design of the Lincoln cent was changed to
        depict the Lincoln Memorial in Washington, D.C. Memorial cents were struck in a copper alloy until 1982, when
        the composition was changed to copper-plated zinc.
      </ProseP>
      <UButtonGroup class="-ms-2.5">
        <TypeSpecifications title="Memorial Cent Specifications" :data="{
          designers: 'Victor D. Brenner (obv), Frank Gasparro (rev)',
          weight: '3.11 grams // 1982-2008: 2.5 grams',
          composition: 'bronze (.950 copper, .050 tin and zinc) // 1982-2008: copper-plated zinc (core: .992 zinc, .008 copper, with a plating of pure copper; total content .975 zinc, .025 copper)',
          diameter: '19 mm',
          edge: 'Plain',
        }" />
      </UButtonGroup>
    </TypeDetail>

    <TypeDetail title="Bicentennial Reverses (2009)" slug="bicentennial" :images="[
      '/cents/lincoln-birth-rev.webp',
      '/cents/lincoln-youth-rev.webp',
      '/cents/lincoln-professional-rev.webp',
      '/cents/lincoln-presidency-rev.webp',
    ]">
      <ProseP>
        In 2009, for the 200th anniversary of Lincoln's birth, four one-year-only reverse designs honoring important
        stages in Abraham Lincoln's life were issued: Birthplace in Kentucky, Formative Years in Indiana, Professional
        Life in Illinois and Presidency in Washington, D.C.
      </ProseP>
      <UButtonGroup class="-ms-2.5">
        <TypeSpecifications title="Bicentennial Cent Specifications" :data="{
          designers: 'Victor D. Brenner (obv), various (revs)',
          weight: '2.5 grams',
          composition: 'copper-plated zinc (core: .992 zinc, .008 copper, with a plating of pure copper; total content .975 zinc, .025 copper)',
          diameter: '19 mm',
          edge: 'Plain',
        }" />
      </UButtonGroup>
    </TypeDetail>

    <TypeDetail title="Shield Reverse (2010 to date)" slug="shield" :images="[
      '/cents/lincoln-shield-obv.webp',
      '/cents/lincoln-shield-rev.webp',
    ]">
      <ProseP>
        The Lincoln cent received a new ongoing reverse design in 2010 featuring a Union Shield, which was widely used
        during the Civil War era and the Lincoln presidency as a symbol of unity.
      </ProseP>
      <UButtonGroup class="-ms-2.5">
        <TypeSpecifications title="Union Cent Specifications" :data="{
          designers: 'Victor D. Brenner (obv), Lyndall Bass (rev)',
          weight: '2.5 grams',
          composition: 'copper-plated zinc (core: .992 zinc, .008 copper, with a plating of pure copper; total content .975 zinc, .025 copper)',
          diameter: '19 mm',
          edge: 'Plain',
        }" />
      </UButtonGroup>
    </TypeDetail>
  </article>
</template>
