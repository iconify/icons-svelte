<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/na4rgbmvw.css';
import '../../css/m/mqt8g0b7o.css';
import '../../css/f/f9guiachc.css';
import '../../css/c/ciatibdic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="na4rgbmvw"/><path class="mqt8g0b7o"/><path class="f9guiachc"/><path class="ciatibdic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trash" {...props}></Icon>
