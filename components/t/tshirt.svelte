<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv_1nabsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rv_1nabsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tshirt" {...props}></Icon>
