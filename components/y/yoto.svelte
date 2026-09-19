<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahv9aqb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahv9aqb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:yoto" {...props}></Icon>
