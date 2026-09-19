<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr52y7bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dr52y7bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:voicemail-forward" {...props}></Icon>
