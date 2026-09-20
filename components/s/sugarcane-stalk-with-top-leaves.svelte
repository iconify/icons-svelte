<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-yr9xtxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z-yr9xtxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sugarcane-stalk-with-top-leaves" {...props}></Icon>
