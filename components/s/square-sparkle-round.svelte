<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3nsdxd1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3nsdxd1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-sparkle-round" {...props}></Icon>
