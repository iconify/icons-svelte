<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkyoe0byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkyoe0byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:skip-next-circle" {...props}></Icon>
