<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0k19hilo.css';
import '../../css/p/ps9svrb0r.css';
import '../../css/n/niyv1hwum.css';
import '../../css/r/rj41gebbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r0k19hilo"/><path class="ps9svrb0r"/><path class="niyv1hwum"/><path class="rj41gebbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shovel-48-bold" {...props}></Icon>
