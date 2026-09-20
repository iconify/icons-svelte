<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_9_jlbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k_9_jlbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:stars-16" {...props}></Icon>
