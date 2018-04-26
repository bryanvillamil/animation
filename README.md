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

el agregara agregara el mixin de button y traera estops estilos de button:

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

------------
### Animaciones

##### Winona

la animacion winona funciona agregando un button con el atributo `data-text=" "` y dentro el valor que deseamos en la animacion dentro del button tendra un span con un texto por defecto. ejemplo:

    <button data-text="Open Project">
    	<span>Open Project</span>
    </button>

**Winona** crea un after dentro y alli agrega en el `content` la propiedad `data-text`, asi da la animacion al button.


## License

The code is open source.

##Bryan Villamil Acevedo
