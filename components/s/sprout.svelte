<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3vs2dt0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3vs2dt0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sprout" {...props}></Icon>
