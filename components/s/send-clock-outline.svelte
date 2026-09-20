<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgxoh_b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgxoh_b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:send-clock-outline" {...props}></Icon>
