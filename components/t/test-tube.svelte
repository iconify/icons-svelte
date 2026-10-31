<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/f0nkw3b3u.css';
import '../../css/d/djvknyp7o.css';
import '../../css/p/psdmkpbst.css';
import '../../css/k/k_nchdcps.css';
import '../../css/i/ieq2ef8aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="f0nkw3b3u wm-shadow"/><path class="djvknyp7o"/><path class="psdmkpbst"/><path class="k_nchdcps"/><path class="ieq2ef8aj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:test-tube" {...props}></Icon>
