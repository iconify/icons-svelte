<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a__s2g6zp.css';
import '../../css/c/cx9zm_rlh.css';
import '../../css/m/m8ofd8byy.css';
import '../../css/b/bn-g92bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="cx9zm_rlh"/><path class="m8ofd8byy"/><path class="bn-g92bbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:street-light-bold" {...props}></Icon>
