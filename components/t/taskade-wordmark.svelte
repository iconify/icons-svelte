<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axem3obyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="axem3obyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:taskade-wordmark" {...props}></Icon>
