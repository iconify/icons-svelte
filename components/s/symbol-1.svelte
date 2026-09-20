<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi36m5bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zi36m5bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:symbol-1" {...props}></Icon>
