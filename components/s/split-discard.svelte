<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1uqju2bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e1uqju2bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:split-discard" {...props}></Icon>
