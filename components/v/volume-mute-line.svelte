<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u30jk17_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u30jk17_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:volume-mute-line" {...props}></Icon>
