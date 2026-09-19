<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeipv6u4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeipv6u4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:slash" {...props}></Icon>
