<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo98_0bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo98_0bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ticket-star-filled" {...props}></Icon>
