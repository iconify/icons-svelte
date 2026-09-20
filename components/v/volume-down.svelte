<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq5pb0owa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wq5pb0owa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volume-down" {...props}></Icon>
