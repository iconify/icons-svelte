<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7llzrb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7llzrb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:socket-eu" {...props}></Icon>
