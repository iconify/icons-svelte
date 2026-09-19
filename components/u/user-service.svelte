<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyrdkflpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fyrdkflpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-service" {...props}></Icon>
