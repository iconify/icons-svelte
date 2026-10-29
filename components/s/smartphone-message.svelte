<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/ch4j9abio.css';
import '../../css/p/pm96j7xxh.css';
import '../../css/w/wiker-buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ch4j9abio"/><path class="pm96j7xxh wm-a"/><path class="wiker-buu wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smartphone-message" {...props}></Icon>
