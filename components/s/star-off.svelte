<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr-rzrbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr-rzrbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:star-off" {...props}></Icon>
