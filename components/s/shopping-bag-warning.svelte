<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi79h_b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi79h_b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shopping-bag-warning" {...props}></Icon>
