<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa71y1b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa71y1b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:triangle-flag" {...props}></Icon>
