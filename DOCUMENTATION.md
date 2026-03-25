# Planification

## Architecture HTML

Cette architecture HTML est simplifiée, mais en général ce sera la structure que je vais suivre,

      body

      
      
        div class = navbar
        
          (code navbar)
          
        /div
      
      
      
        div class = hero
        
          (code hero)
          
        /div
      
      
      
        div class = card--about
        
          (code card--about)
          
        /div
      
      
      
        div class = card--products
        
          (code card--products)  
          
        /div
      
      
        
        div class = card--hours
      
          (code card--hours)  
          
        /div
      
        
      
        div class = testimonials
        
          (code testimonials)  
          
        /div
      
      
      
        div class = media-object
        
          (code media-object)  
          
        /div



        div class = card--pricing
        
          (code card--pricing)  
          
        /div


      
        div class = card--contact
        
          (code card--contact)  
          
        /div
      

        
        form
        
          (code form)  
          
        /form

      
      
        footer
        
          (code footer)  
          
        /footer


  
      /body

## Composants réutilisables et nomenclature des classes

### Boutons:

**button**

**button--learn-more**

**button--order**

**button--cancel**


### Carte:

**card**

**card__title**

**card__subtitle**

### Barre de navigation: 

**navbar**

**navbar__title**

**navbar__logo**

### Section hero: 

**hero**

**hero__title**

**hero__title__color**

**hero__subtitle**

**hero__image**

**hero__button__right**

**hero__button__left**

### Carte (à propos):

**card--about**

**card--about__title**

**card--about__subtitle**

**card--about__right-section**

**card--about__left-section**

**card--about__bottom-section**

### Carte (produits): 

**card--products**

**card--products__left-product**

**card--products__middle-product**

**card--products__right-product**

**card--products__badge**

**card--products__name**

**card--products__description**

### Carte (heures d'ouvertures): 

**card--hours**
**card--hours__section**
**card--hours__icon**
**card--hours__day**
**card--hours__hour**


### Article de blogue (témoignages): 

**testimonials**

**testimonials__title**

**testimonials__avatar**

**testimonials__name**

**testimonials__comment**

### Liste de médias (équipes): 

**media-object**

**media-object__title**

**media-object__subtitle**

**media-object__icon**

**media-object__avatar**

**media-object__name**

**media-object__description**

### Grille de prix: 

**card--pricing**

**card--pricing__section**

**card--pricing__name**

**card--pricing__price**

**card--pricing__description**


### Carte (Section nous joindre): 

**card--contact**

**card--contact__subtitle**

**card--contact__map**


### Formulaire: 

**form**

**form__title**

**form__input**

### Menu de pied de page: 

**footer**

**footer__section__title**

**footer__section**

**footer__map__title**

**footer__map**

## Système de tokens (variables) à utiliser<

  --color-primary: #2a9d8f;
  --color-secondary: #e9c46a;
  --color-accent: #f4a261;
  --color-bg-dark: #264653;
  --color-bg: #ffffff;
  --color-bg-grey: #ebeff0;
  --color-text: #1a2e1a;
  --color-text-secondary: #ffffff;

  /* Espacements */
  --space-2xs: 2px;
  --space-xs: 4px;
  --space-sm: 8px;
  --space-md: 16px;
  --space-lg: 24px;
  --space-xl: 32px;
  --space-2xl: 46px;
  --space-3xl: 60px;

  /* Typographie */
  --font-size-sm: 0.8rem;
  --font-size-base: 1rem;
  --font-size-lg: 1.2rem;
  --font-size-xl: 1.6rem;
  --font-size-2xl: 2rem;

  /* Bordures */
  --radius-sm: 5px;
  --radius-md: 8px;
  --radius-lg: 10px;
  --radius-full: 9999px;

  # Difficultés rencontreés
-Manque de temps
-Manque d'expérience
-Comprehension des instructions
