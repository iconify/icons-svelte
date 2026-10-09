<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7_yqvbof.css';
import '../../css/v/vf15g1hye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x7_yqvbof"/><path class="vf15g1hye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:save-48" {...props}></Icon>
