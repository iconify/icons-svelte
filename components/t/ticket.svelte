<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pafp66bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pafp66bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:ticket" {...props}></Icon>
