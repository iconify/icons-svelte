<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbes-8bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbes-8bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:virus" {...props}></Icon>
