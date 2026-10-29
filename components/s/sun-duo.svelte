<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/ll9crmb_e.css';
import '../../css/z/zs295v-ni.css';
import '../../css/y/yi23eea4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ll9crmb_e"/><path class="wm-a zs295v-ni"/><path class="yi23eea4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sun-duo" {...props}></Icon>
