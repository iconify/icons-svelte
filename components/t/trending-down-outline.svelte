<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wev0scb4m.css';
import '../../css/m/mi0qv-kbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wev0scb4m"/><path class="mi0qv-kbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:trending-down-outline" {...props}></Icon>
