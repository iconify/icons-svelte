<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8lajlb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="x8lajlb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:smoking" {...props}></Icon>
