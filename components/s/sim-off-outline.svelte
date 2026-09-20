<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifuftsm3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifuftsm3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sim-off-outline" {...props}></Icon>
