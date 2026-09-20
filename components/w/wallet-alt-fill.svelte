<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l5ffbwm9z.css';
import '../../css/e/e4o4fibdr.css';
import '../../css/p/py7ktqbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)" class="cuyn6tgcc"><path class="l5ffbwm9z"/><path clip-rule="evenodd" class="e4o4fibdr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:wallet-alt-fill" {...props}></Icon>
