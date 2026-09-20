<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3_7o7bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3_7o7bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:triangle-down-outline" {...props}></Icon>
