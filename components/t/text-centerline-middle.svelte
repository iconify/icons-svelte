<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncuisqljf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncuisqljf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-centerline-middle" {...props}></Icon>
