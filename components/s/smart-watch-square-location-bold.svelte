<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzlnpvced.css';
import '../../css/v/vmfgchi1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzlnpvced"/><path class="vmfgchi1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smart-watch-square-location-bold" {...props}></Icon>
