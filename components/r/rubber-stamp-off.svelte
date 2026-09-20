<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id2dg3ljq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id2dg3ljq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rubber-stamp-off" {...props}></Icon>
