<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsa50vz8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="xsa50vz8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shoe-prints" {...props}></Icon>
