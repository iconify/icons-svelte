<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq9shcbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iq9shcbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:watch-2" {...props}></Icon>
