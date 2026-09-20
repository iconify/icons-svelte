<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rptrf_b-m.css';
import '../../css/p/pghzzobog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rptrf_b-m"/><path class="pghzzobog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:we-chat" {...props}></Icon>
