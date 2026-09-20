<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umps4yb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="umps4yb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wave-square-solid" {...props}></Icon>
