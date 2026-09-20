<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sofbzo8xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sofbzo8xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:volume-up" {...props}></Icon>
