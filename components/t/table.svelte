<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv0lq0-ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tv0lq0-ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:table" {...props}></Icon>
