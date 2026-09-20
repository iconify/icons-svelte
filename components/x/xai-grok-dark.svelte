<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0maw-bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":841.89,"height":595.28};
const content = `<path class="e0maw-bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xai-grok-dark" {...props}></Icon>
