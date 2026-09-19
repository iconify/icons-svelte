<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii8jenblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ii8jenblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:scroll-torah" {...props}></Icon>
