<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy9v6jbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fy9v6jbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-mask-solid" {...props}></Icon>
