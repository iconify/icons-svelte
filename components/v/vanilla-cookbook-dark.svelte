<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u91jgo_1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u91jgo_1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vanilla-cookbook-dark" {...props}></Icon>
