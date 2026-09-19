<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il6iivpjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il6iivpjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tilt-window-opened" {...props}></Icon>
