<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd31iab1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd31iab1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:valve" {...props}></Icon>
