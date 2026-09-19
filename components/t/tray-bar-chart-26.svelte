<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwat5bb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="kwat5bb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tray-bar-chart-26" {...props}></Icon>
