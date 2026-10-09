<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc7985b_u.css';
import '../../css/s/sy7hkneln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cc7985b_u"/><path class="sy7hkneln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scope-1-20-bold" {...props}></Icon>
