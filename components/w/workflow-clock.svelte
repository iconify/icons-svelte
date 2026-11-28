<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxc7bbcbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxc7bbcbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:workflow-clock" {...props}></Icon>
