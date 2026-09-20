<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5z-5bcwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h5z-5bcwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:skip-filled" {...props}></Icon>
