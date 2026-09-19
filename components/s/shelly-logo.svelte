<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh_c97dbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh_c97dbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shelly-logo" {...props}></Icon>
