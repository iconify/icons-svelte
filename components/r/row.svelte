<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuvq0wb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="vuvq0wb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:row" {...props}></Icon>
