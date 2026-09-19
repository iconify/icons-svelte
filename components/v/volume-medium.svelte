<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/raliu5b3x.css';
import '../../css/d/d1olnibrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="raliu5b3x"/><path class="d1olnibrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:volume-medium" {...props}></Icon>
