<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo8zr4c7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo8zr4c7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ubuntu-line" {...props}></Icon>
