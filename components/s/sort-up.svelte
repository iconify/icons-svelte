<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0dhnlbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="n0dhnlbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-up" {...props}></Icon>
