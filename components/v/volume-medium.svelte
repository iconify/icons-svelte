<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i75-_3t5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="i75-_3t5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:volume-medium" {...props}></Icon>
