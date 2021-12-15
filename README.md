# CV_pagedown
Mi CV con el paquete pagedown de R
Este paquete permite cargar un CV en HTML o PDF con foto, iconos, línea de tiempo y apartado para skills o lo que se guste poner. Requiere instalar los paquetes pagedown y rmarkdown y usar un template llamado HTML resume. El .rmd contiene un encabezado YAML con una variable self_contained que según se determinte TRUE o FALSE renderiza un html. Luego contiene otra variable knit comentada, que si se descomenta renderiza un pdf.
