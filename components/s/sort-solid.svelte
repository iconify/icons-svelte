<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm4qh8gpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm4qh8gpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sort-solid" {...props}></Icon>
