<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rymil3blb.css';
import '../../css/x/x739a3bax.css';
import '../../css/e/eewbnjvit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rymil3blb"/><path class="x739a3bax"/><path class="eewbnjvit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-9-duo" {...props}></Icon>
