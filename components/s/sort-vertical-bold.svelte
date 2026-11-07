<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0nj5essx.css';
import '../../css/t/tl8qmubzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0nj5essx"/><path class="tl8qmubzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-vertical-bold" {...props}></Icon>
