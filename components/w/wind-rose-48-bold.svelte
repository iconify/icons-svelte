<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn158vbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gn158vbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-rose-48-bold" {...props}></Icon>
