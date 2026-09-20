<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyw7qtbor.css';
import '../../css/g/g-an08bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyw7qtbor"/><path class="g-an08bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:server-refresh-1-bold" {...props}></Icon>
