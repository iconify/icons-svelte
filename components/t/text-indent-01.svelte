<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy1unsnmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy1unsnmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-indent-01" {...props}></Icon>
