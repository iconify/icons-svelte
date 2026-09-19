<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmoip1aun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1408};
const content = `<path class="vmoip1aun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:shopping-cart" {...props}></Icon>
