<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3nyc0bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="z3nyc0bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:space-shuttle" {...props}></Icon>
