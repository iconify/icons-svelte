<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwp8pzb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dwp8pzb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:wifi-antenna-solid" {...props}></Icon>
