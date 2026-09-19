<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs8k-2cze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rs8k-2cze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:view-mode" {...props}></Icon>
