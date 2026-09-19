<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra46yxsdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra46yxsdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-intersect-alt-filled" {...props}></Icon>
