<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us0x9w4kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="us0x9w4kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:save-template" {...props}></Icon>
