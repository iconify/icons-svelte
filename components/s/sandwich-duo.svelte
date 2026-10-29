<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qrfxe7bdo.css';
import '../../css/h/h8wb40b9m.css';
import '../../css/x/xac-pkbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qrfxe7bdo"/><path class="h8wb40b9m wm-a"/><path class="xac-pkbvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sandwich-duo" {...props}></Icon>
