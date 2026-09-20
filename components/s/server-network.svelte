<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdj631veg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdj631veg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:server-network" {...props}></Icon>
