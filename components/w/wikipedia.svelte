<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7g50lben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7g50lben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:wikipedia" {...props}></Icon>
