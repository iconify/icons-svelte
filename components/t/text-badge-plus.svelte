<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr3w4h4-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xr3w4h4-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-badge-plus" {...props}></Icon>
