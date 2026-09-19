<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc--4bcdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lc--4bcdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:suit-spade-fill" {...props}></Icon>
