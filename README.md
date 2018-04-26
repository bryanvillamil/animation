# Libreria de animation

### Botones

Esta libreria fue echa con **SCSS(SASS)**, se basa en importar en el index o en el mismo sass(import) el archivo llamado animation.css o animation.min.css alli traera todos los estilos efectos y animaciones a los diferentes componentes.

------------

#### Archivo Animation

el archivo animation tiene mixin agregados con sass.

el archivo inicia con los estilos generales para todos los botones el cual se usa solo incluyendolo al button deseado asi:

    button {
          @include button;
    }

el agregara el mixin del button y traera estos estilos de este:

    @mixin button {
    	display: flex;
    	align-items: center;
    	justify-content: center;
    	padding: 1em 2em;
    	border: none;
    	cursor: pointer;
    	position: relative;
    	z-index: 1;
    	-webkit-backface-visibility: hidden;
    	-moz-osx-font-smoothing: grayscale;
    	&:focus {
    		outline: none;
    	}
    }

## Animaciones Botones
hay 20 animaciones diferentes para estilar botones:

#### Winona
------------


## License

The code is open source.

#### Bryan Villamil Acevedo
