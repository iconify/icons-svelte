<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjo-3lbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zjo-3lbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:water-tower-14" {...props}></Icon>
