<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g36zgr.css';
import '../../css/m/mux-7n.css';
import '../../css/c/cx-from-17px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g36zgr"/><circle class="mux-7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:switch-to-switch-off-transition" {...props}></Icon>
