<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txxkrmb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="txxkrmb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:volume-xmark" {...props}></Icon>
