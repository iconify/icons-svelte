<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj5fy7p2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj5fy7p2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sapling" {...props}></Icon>
