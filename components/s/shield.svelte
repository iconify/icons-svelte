<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy7gb0z0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="oy7gb0z0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:shield" {...props}></Icon>
