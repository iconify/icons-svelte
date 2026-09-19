<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezp74yeys.css';
import '../../css/k/k_7pasz5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<defs><path id="SVGcKbddeti" class="ezp74yeys"/></defs><g class="k_7pasz5l"><use href="#SVGcKbddeti"/><use href="#SVGcKbddeti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:tilde" {...props}></Icon>
