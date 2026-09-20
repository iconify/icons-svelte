<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zat5fobrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zat5fobrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:ticket-minus" {...props}></Icon>
