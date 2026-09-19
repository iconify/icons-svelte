<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy51f2wrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zy51f2wrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-turn-left-fill" {...props}></Icon>
