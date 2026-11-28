<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkt3i8kst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkt3i8kst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-square-plus" {...props}></Icon>
