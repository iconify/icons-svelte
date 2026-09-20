<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0-h-waps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n0-h-waps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:trash-alt-solid" {...props}></Icon>
