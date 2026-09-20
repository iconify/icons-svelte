<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l201mbccu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="l201mbccu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:subtract-1" {...props}></Icon>
