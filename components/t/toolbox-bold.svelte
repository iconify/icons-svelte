<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w06k5-7cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w06k5-7cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:toolbox-bold" {...props}></Icon>
