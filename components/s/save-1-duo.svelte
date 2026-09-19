<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lg6-jzvbp.css';
import '../../css/m/mc3fvym9s.css';
import '../../css/c/cpj3bqbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lg6-jzvbp"/><path class="mc3fvym9s"/><path class="cpj3bqbqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:save-1-duo" {...props}></Icon>
