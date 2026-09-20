<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdeyaq8zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xdeyaq8zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:star-half-solid" {...props}></Icon>
