<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i79c0yxye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i79c0yxye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:yelp" {...props}></Icon>
