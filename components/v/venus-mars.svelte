<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyg7nbc4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1792};
const content = `<path class="wyg7nbc4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:venus-mars" {...props}></Icon>
