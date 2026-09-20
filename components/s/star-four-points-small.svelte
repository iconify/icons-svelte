<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rznymrz9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rznymrz9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-four-points-small" {...props}></Icon>
