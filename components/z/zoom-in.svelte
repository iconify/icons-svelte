<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuv8fabei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fuv8fabei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:zoom-in" {...props}></Icon>
