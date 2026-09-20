<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbren1b0h.css';
import '../../css/n/n2xns2dzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<g class="sbren1b0h"><g id="SVGC8RjHw2T" transform="translate(150 150)"><path id="SVGCQNsheVl" class="n2xns2dzg"/><use href="#SVGCQNsheVl" transform="rotate(45)"/><use href="#SVGCQNsheVl" transform="rotate(90)"/><use href="#SVGCQNsheVl" transform="rotate(135)"/></g></g><use href="#SVGC8RjHw2T"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:svg" {...props}></Icon>
