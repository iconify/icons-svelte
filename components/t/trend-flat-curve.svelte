<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3gqaxbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z3gqaxbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:trend-flat-curve" {...props}></Icon>
