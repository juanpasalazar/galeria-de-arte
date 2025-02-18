Online Art Gallery

📌 Project Overview

Website: Naranjovelilla.comPurpose: Online Art GalleryTechnologies Used: WordPress, Elementor, Elementor Pro, Custom Post Types (CPT UI), Advanced Custom Fields (ACF)

This project was developed to enable the addition of artworks and artists into WordPress and to display:

Each artwork with its assigned artist.

Each artist with all the artworks linked to them.

On an artwork page, other artworks from the same artist.

📌 Custom Post Types (CPT)

1️⃣ Artworks (obras-de-arte)

Label: Obras

Singular Label: Obra

Description: Available artworks

Has archive: ✅ Yes

Public: ✅ Yes

Show in REST API: ✅ Yes

Menu Icon: dashicons-format-image

Supports: Title

Rewrite Enabled: ✅ Yes

2️⃣ Artists (autores)

Label: Autores

Singular Label: Autor

Public: ✅ Yes

Has archive: ✅ Yes

Show in REST API: ✅ Yes

Menu Icon: dashicons-admin-users

Supports: Title

Rewrite Enabled: ✅ Yes

📌 Advanced Custom Fields (ACF)

Artist Fields (autores)

nombre_del_autor (Text)

ano_nacimiento (Text)

ano_muerte (Text)

bio_del_artista (Textarea)

perfil_instagram (URL)

website (URL)

foto_del_artista (Image)

obras_del_artista (Post Object - Linked to Artworks)

Artwork Fields (obras-de-arte)

nombre_de_la_obra (Text)

nombre_del_autor (Post Object - Linked to Artists)

fecha_nacimiento_autor (Text)

dimensiones_de_la_obra (Text)

descripcion_de_obra (Textarea)

material_o_tecnica_de_elaboracion (Text)

peso_aproximado (Text)

ano_de_la_obra (Text)

imagen_de_la_obra (Image)

📌 Implemented Shortcodes


