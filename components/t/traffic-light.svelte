<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on9_x8i1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="on9_x8i1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:traffic-light" {...props}></Icon>
