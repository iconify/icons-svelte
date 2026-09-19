<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbfb1bccc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wbfb1bccc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:voice-mode" {...props}></Icon>
