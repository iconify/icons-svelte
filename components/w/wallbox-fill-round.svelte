<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0prtnwti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0prtnwti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wallbox-fill-round" {...props}></Icon>
