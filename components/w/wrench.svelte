<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkz-23bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pkz-23bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wrench" {...props}></Icon>
