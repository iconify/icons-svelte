<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uohix1b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uohix1b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:shoes-14" {...props}></Icon>
