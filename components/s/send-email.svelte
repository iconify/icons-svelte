<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-0nc7mfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p-0nc7mfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:send-email" {...props}></Icon>
