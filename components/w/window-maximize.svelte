<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xopn4tb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xopn4tb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:window-maximize" {...props}></Icon>
