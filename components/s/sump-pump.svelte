<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apx8kl_5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apx8kl_5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sump-pump" {...props}></Icon>
