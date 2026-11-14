<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_vbl7t9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_vbl7t9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:volvo-alt" {...props}></Icon>
