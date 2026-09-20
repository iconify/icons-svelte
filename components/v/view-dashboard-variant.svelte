<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbnjyebwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbnjyebwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-dashboard-variant" {...props}></Icon>
