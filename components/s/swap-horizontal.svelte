<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouk9fb6fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ouk9fb6fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:swap-horizontal" {...props}></Icon>
