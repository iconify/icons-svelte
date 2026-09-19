<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nqqj806mv.css';
import '../../css/b/b-us7aczi.css';
import '../../css/r/rkoiybc7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nqqj806mv"/><path class="b-us7aczi"/><path class="rkoiybc7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ruler-combined-duo" {...props}></Icon>
