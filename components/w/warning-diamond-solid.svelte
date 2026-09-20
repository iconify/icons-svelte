<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkgmy2hyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vkgmy2hyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:warning-diamond-solid" {...props}></Icon>
