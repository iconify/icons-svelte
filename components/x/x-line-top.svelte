<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryquvccfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryquvccfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:x-line-top" {...props}></Icon>
