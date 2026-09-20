<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpeweo4gr.css';
import '../../css/h/hl2ro6kwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qpeweo4gr"/><path class="hl2ro6kwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:technology-robot-ai-signal-2" {...props}></Icon>
