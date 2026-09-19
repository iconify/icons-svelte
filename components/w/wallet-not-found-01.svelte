<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/busrn3bwc.css';
import '../../css/w/worcco0zv.css';
import '../../css/e/eswimnb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="busrn3bwc"/><path class="worcco0zv"/><path class="eswimnb4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wallet-not-found-01" {...props}></Icon>
