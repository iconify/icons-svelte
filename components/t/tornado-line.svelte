<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f829fhb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f829fhb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tornado-line" {...props}></Icon>
