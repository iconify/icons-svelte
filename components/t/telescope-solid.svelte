<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayz3-lg7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ayz3-lg7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:telescope-solid" {...props}></Icon>
