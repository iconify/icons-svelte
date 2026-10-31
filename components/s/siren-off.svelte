<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju2jembnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju2jembnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:siren-off" {...props}></Icon>
