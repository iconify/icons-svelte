<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4_7t_bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4_7t_bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sorting-04" {...props}></Icon>
