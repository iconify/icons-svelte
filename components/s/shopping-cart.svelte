<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppdy_ccdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ppdy_ccdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:shopping-cart" {...props}></Icon>
