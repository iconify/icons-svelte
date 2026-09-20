<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgulhuyjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tgulhuyjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:zip-folder" {...props}></Icon>
