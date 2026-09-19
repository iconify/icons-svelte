<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaaayhocs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zaaayhocs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:session-in-progress-compact" {...props}></Icon>
