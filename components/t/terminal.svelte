<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv8oerjzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1360,"height":1000};
const content = `<path class="vv8oerjzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:terminal" {...props}></Icon>
