<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8zd07bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g8zd07bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:sos-help-emergency-sign-remix" {...props}></Icon>
