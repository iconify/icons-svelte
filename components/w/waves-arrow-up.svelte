<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhu5zrben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhu5zrben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:waves-arrow-up" {...props}></Icon>
