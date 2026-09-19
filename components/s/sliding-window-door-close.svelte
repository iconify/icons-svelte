<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqu95vijs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqu95vijs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sliding-window-door-close" {...props}></Icon>
