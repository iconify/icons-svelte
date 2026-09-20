<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3__g_bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i3__g_bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:spinner-solid" {...props}></Icon>
