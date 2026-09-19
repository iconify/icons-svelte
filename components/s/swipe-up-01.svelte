<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slfwtsbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slfwtsbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-up-01" {...props}></Icon>
