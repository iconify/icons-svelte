<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdcc0qd_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdcc0qd_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:typewriter" {...props}></Icon>
