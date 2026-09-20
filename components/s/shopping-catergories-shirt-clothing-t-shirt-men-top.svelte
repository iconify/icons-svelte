<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7ze1_r8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f7ze1_r8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-catergories-shirt-clothing-t-shirt-men-top" {...props}></Icon>
