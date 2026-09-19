<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfj6xu_3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="lfj6xu_3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:virus-slash" {...props}></Icon>
