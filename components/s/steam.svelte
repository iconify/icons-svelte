<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j48cub3np.css';
import '../../css/b/bg6fy62nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j48cub3np"/><path class="bg6fy62nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:steam" {...props}></Icon>
