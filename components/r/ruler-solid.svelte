<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvnte8biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xvnte8biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ruler-solid" {...props}></Icon>
