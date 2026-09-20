<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmdvb9gaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rmdvb9gaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:split-vertical-flat" {...props}></Icon>
