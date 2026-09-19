<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f57e4fxjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":482,"height":512};
const content = `<path class="f57e4fxjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:ussunnah" {...props}></Icon>
