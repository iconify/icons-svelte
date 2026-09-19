<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd1_kjbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="yd1_kjbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:truck" {...props}></Icon>
