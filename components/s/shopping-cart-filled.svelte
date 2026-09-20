<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4uo92wkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k4uo92wkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shopping-cart-filled" {...props}></Icon>
