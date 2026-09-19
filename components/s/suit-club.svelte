<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjm8lsc9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gjm8lsc9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:suit-club" {...props}></Icon>
