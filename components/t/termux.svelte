<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j1z-x8bgg.css';
import '../../css/d/da4op8ghx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="ft5dv1b6b"><path class="j1z-x8bgg"/><path class="da4op8ghx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:termux" {...props}></Icon>
