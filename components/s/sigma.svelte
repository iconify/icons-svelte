<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/l/ldjhm2bpx.css';
import '../../css/l/lu_jwkbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="ldjhm2bpx"/><path class="lu_jwkbsc wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:sigma" {...props}></Icon>
