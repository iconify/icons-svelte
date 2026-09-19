<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn55ge7zx.css';
import '../../css/p/pyk3u23xc.css';
import '../../css/m/mrpnast4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="tn55ge7zx"><path class="pyk3u23xc"/><path class="mrpnast4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:user-bold" {...props}></Icon>
