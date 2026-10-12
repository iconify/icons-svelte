<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5jsvcc-v.css';
import '../../css/g/gszf-lm8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f5jsvcc-v"/><path class="gszf-lm8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whiteboard-48" {...props}></Icon>
