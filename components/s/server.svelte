<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpslaerpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpslaerpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:server" {...props}></Icon>
