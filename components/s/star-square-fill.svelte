<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fdqqok9ep.css';
import '../../css/i/iazw9mnub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGExGR1bRm)"><path class="fdqqok9ep"/></g><defs><clipPath id="SVGExGR1bRm"><path class="iazw9mnub"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:star-square-fill" {...props}></Icon>
