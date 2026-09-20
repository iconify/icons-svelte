<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fifpa4b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fifpa4b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-bold" {...props}></Icon>
