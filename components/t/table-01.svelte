<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys_306b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys_306b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:table-01" {...props}></Icon>
