<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzi2x3e-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzi2x3e-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tooltip-user" {...props}></Icon>
