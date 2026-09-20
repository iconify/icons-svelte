<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5rhi4beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a5rhi4beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:split-vertical" {...props}></Icon>
