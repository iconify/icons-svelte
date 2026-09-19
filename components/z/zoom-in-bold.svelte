<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg3_1fb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg3_1fb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:zoom-in-bold" {...props}></Icon>
