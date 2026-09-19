<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4y5kochc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n4y5kochc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:sparkle-compact" {...props}></Icon>
