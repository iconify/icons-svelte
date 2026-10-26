<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nsfr-ie6p.css';
import '../../css/p/p1o8i6baa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":360};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGx5gPieiZ)"><path class="nsfr-ie6p"/></g><defs><clipPath id="SVGx5gPieiZ"><path class="p1o8i6baa"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:userpilot-dark" {...props}></Icon>
