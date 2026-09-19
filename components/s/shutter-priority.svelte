<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g7c0sab9y.css';
import '../../css/n/n7whz5z0y.css';
import '../../css/h/h03pf40ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="g7c0sab9y"/><path class="n7whz5z0y"/><path class="h03pf40ov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:shutter-priority" {...props}></Icon>
