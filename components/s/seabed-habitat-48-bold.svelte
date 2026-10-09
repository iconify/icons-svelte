<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6cvwtbsp.css';
import '../../css/r/r4a32cb3q.css';
import '../../css/r/raz-mzj-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d6cvwtbsp"/><path class="r4a32cb3q"/><path class="raz-mzj-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seabed-habitat-48-bold" {...props}></Icon>
