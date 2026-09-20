<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyyljm02h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyyljm02h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unfold-less-vertical" {...props}></Icon>
