<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir5hywcvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ir5hywcvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:volume-increase" {...props}></Icon>
