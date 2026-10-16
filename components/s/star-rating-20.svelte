<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg5jh0yog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vg5jh0yog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:star-rating-20" {...props}></Icon>
