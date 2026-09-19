<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycm4o3bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycm4o3bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:thought-bubble" {...props}></Icon>
