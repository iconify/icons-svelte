<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw_r6bbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="hw_r6bbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-arrow-up-right" {...props}></Icon>
