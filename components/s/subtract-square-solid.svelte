<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ico9cn5px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ico9cn5px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:subtract-square-solid" {...props}></Icon>
