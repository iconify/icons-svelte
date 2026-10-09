<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljsp6_b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ljsp6_b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:underline-20-bold" {...props}></Icon>
