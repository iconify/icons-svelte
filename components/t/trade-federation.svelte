<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmw063b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gmw063b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:trade-federation" {...props}></Icon>
