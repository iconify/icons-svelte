<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl4t1zbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl4t1zbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-warning-fill-round" {...props}></Icon>
