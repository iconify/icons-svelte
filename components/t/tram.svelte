<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8nq4o_1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c8nq4o_1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tram" {...props}></Icon>
