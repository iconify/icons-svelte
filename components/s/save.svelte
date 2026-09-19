<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h5qhce_5u.css';
import '../../css/h/hiqoehyvg.css';
import '../../css/w/wxit8d4zv.css';
import '../../css/r/rs84ae6xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="h5qhce_5u"/><path clip-rule="evenodd" class="hiqoehyvg"/><path class="wxit8d4zv"/><path class="rs84ae6xb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:save" {...props}></Icon>
