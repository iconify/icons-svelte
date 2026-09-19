<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcczw9bad.css';
import '../../css/u/u5k1hcfaz.css';
import '../../css/j/jp-5skmgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wcczw9bad"><path class="u5k1hcfaz"/><path class="jp-5skmgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:stream-bold" {...props}></Icon>
