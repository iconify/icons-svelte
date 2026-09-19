<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6k5j8bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n6k5j8bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:scissors" {...props}></Icon>
