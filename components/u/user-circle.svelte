<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl5uzhbhz.css';
import '../../css/e/egfpnrb2n.css';
import '../../css/i/i07gwburj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl5uzhbhz"/><path class="egfpnrb2n"/><path class="i07gwburj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:user-circle" {...props}></Icon>
