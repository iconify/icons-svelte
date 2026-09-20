<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqkav9c8l.css';
import '../../css/b/bpfu64dcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqkav9c8l"/><path class="bpfu64dcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smartphone-app-widget-translator" {...props}></Icon>
