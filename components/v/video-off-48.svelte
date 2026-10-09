<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd6fc7nov.css';
import '../../css/m/mxvx73bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pd6fc7nov"/><path class="mxvx73bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-off-48" {...props}></Icon>
