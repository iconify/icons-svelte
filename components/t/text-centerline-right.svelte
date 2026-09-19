<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fykl5sbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fykl5sbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-centerline-right" {...props}></Icon>
