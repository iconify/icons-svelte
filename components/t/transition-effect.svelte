<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-y-j6fsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f-y-j6fsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:transition-effect" {...props}></Icon>
