<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft1yr5mlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ft1yr5mlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:star-empty" {...props}></Icon>
