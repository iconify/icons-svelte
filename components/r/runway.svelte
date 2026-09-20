<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pzhbybbyg.css';
import '../../css/w/wp_2lsbjz.css';
import '../../css/m/mhy3-ifmz.css';
import '../../css/p/pin2338sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGDTtXObki)"><path class="pzhbybbyg"/><path class="wp_2lsbjz"/><path class="mhy3-ifmz"/></g><defs><clipPath id="SVGDTtXObki"><path class="pin2338sh"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:runway" {...props}></Icon>
