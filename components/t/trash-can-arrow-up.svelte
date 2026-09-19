<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1h5u9bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="u1h5u9bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:trash-can-arrow-up" {...props}></Icon>
