<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqxfm3x3o.css';
import '../../css/r/rwuxsc6cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqxfm3x3o"/><path class="rwuxsc6cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:train-3" {...props}></Icon>
