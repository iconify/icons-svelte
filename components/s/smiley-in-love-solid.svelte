<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_svr_bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x_svr_bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-in-love-solid" {...props}></Icon>
