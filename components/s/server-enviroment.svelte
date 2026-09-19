<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-ju5ccij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x-ju5ccij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:server-enviroment" {...props}></Icon>
