<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqmsawb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqmsawb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:voice-scan-1" {...props}></Icon>
