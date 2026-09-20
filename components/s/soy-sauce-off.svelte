<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmhcycc2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmhcycc2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:soy-sauce-off" {...props}></Icon>
