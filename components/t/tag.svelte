<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti37xlb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ti37xlb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tag" {...props}></Icon>
