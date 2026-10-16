<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh3g0ib5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hh3g0ib5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-star-20" {...props}></Icon>
