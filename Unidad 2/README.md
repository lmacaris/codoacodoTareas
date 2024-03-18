### Tarea 2 - Codo a Codo.

1-  Crea un archivo HTML que contenga una tabla e investigá: ¿Cómo podrías insertar un video de YouTube en una celda de la tabla ?

Se puede insertar un video de youtube de la siguente manera utilizando iframe:
			``` html
			<table>
			  <tr>
			    <td>
			      <iframe width="560" height="315" src="https://www.youtube.com/embed/Ki_0iES2cGI?si=_2HO14KMm-9mgVyl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
			    </td>
			    <td>
			      <!-- Other table data cells -->
			    </td>
			  </tr>
			  <!-- Additional rows if needed -->
			</table>
			```