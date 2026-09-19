<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbw7f2xxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dbw7f2xxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sack-dollar" {...props}></Icon>
