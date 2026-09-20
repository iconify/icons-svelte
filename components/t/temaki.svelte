<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylas96bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ylas96bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:temaki" {...props}></Icon>
