<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk5xcim_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yk5xcim_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:square-plus" {...props}></Icon>
