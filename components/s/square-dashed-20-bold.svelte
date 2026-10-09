<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghzll71qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ghzll71qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-dashed-20-bold" {...props}></Icon>
