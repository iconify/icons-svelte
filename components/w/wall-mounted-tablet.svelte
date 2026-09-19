<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqfjexbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqfjexbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-mounted-tablet" {...props}></Icon>
