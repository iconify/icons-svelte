<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgrr-s0ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgrr-s0ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sync-box-alt" {...props}></Icon>
