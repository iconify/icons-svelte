<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iympo7t3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iympo7t3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:voice-scan-2" {...props}></Icon>
