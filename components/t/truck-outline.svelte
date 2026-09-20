<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du5cymr0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du5cymr0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-outline" {...props}></Icon>
