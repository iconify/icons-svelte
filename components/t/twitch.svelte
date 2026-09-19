<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czz9dlbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="czz9dlbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:twitch" {...props}></Icon>
