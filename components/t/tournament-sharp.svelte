<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p67rcgjto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p67rcgjto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:tournament-sharp" {...props}></Icon>
