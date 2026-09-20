<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm7_nacmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="dm7_nacmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:voice-scan-2" {...props}></Icon>
