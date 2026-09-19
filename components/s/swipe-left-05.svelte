<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y74gqacjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y74gqacjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-left-05" {...props}></Icon>
