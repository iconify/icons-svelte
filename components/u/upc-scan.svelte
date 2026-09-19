<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp6hhk2lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kp6hhk2lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:upc-scan" {...props}></Icon>
