<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvbu6bbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qvbu6bbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:voice-mode-compact" {...props}></Icon>
