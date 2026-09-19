<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oyxvwvb9z.css';
import '../../css/v/v2-sg-bdy.css';
import '../../css/n/nxpruiwiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="oyxvwvb9z"/><path class="v2-sg-bdy"/><path class="nxpruiwiw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tools-duo" {...props}></Icon>
