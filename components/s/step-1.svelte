<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6s-y4r-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y6s-y4r-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:step-1" {...props}></Icon>
