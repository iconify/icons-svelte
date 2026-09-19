<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6_7uibvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6_7uibvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:zoom-out" {...props}></Icon>
