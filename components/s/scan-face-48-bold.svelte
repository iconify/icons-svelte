<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq2pmabsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qq2pmabsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-face-48-bold" {...props}></Icon>
