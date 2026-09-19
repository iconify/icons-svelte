<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tz_gf3e9g.css';
import '../../css/f/f0gpxfb_w.css';
import '../../css/e/eturhmkap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tz_gf3e9g"/><path class="f0gpxfb_w"/><circle class="eturhmkap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:video-01" {...props}></Icon>
