<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz9el0b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yz9el0b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:star-fill-20" {...props}></Icon>
