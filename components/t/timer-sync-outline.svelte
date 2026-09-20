<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwmm88bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwmm88bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-sync-outline" {...props}></Icon>
