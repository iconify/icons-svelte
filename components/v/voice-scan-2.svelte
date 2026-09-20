<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_iigfb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="b_iigfb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:voice-scan-2" {...props}></Icon>
