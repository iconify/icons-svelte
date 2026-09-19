<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mav5rmb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mav5rmb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zoomout" {...props}></Icon>
