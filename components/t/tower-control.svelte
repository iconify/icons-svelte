<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoksa15fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoksa15fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tower-control" {...props}></Icon>
