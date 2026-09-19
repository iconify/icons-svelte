<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh6lj8bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wh6lj8bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sunset-fill" {...props}></Icon>
