<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-y0p4f_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-y0p4f_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sort-number-asc" {...props}></Icon>
