<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6z-b0byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6z-b0byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shaka-04" {...props}></Icon>
