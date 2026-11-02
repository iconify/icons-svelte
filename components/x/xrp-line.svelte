<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es6ihinkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es6ihinkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:xrp-line" {...props}></Icon>
