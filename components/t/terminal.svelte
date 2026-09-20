<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4yqj4bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4yqj4bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:terminal" {...props}></Icon>
