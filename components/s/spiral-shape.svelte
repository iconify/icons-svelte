<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp6l-5t5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lp6l-5t5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:spiral-shape" {...props}></Icon>
