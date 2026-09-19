<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiu1h3tlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiu1h3tlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:yelp" {...props}></Icon>
