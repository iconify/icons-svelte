<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4x8d4z4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s4x8d4z4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-circle" {...props}></Icon>
