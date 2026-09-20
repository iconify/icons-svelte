<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw9u178af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gw9u178af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:settings" {...props}></Icon>
