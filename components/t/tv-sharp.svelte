<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sktlhcxdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sktlhcxdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:tv-sharp" {...props}></Icon>
