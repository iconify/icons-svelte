<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st-ub119n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st-ub119n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sapling-filled" {...props}></Icon>
