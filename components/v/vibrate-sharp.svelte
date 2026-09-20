<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcrccabpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcrccabpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:vibrate-sharp" {...props}></Icon>
