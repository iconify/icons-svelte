<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfhnyzbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wfhnyzbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:volume-level-high-solid" {...props}></Icon>
