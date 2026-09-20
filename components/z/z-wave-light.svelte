<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjcbap7vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjcbap7vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:z-wave-light" {...props}></Icon>
