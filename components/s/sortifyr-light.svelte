<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg38t_b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eg38t_b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sortifyr-light" {...props}></Icon>
