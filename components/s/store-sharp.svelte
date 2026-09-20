<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbw1u09ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbw1u09ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:store-sharp" {...props}></Icon>
