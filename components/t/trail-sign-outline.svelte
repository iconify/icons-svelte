<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lemsw-boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lemsw-boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trail-sign-outline" {...props}></Icon>
