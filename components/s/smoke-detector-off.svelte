<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flw9b1kuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flw9b1kuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smoke-detector-off" {...props}></Icon>
