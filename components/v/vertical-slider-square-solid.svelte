<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t__mzi6ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t__mzi6ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:vertical-slider-square-solid" {...props}></Icon>
