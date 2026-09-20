<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czzlbxmws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="czzlbxmws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sail-ship-solid" {...props}></Icon>
