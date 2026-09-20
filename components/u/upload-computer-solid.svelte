<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0t33gbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i0t33gbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:upload-computer-solid" {...props}></Icon>
