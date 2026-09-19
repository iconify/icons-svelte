<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfr8ntbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfr8ntbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shutter-40" {...props}></Icon>
