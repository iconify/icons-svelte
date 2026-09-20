<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6f4avb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6f4avb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-sync" {...props}></Icon>
