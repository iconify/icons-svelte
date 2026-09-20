<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w331e2k4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w331e2k4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tea-outline" {...props}></Icon>
